<h1>Command Line Cheat Sheet for Beginners</h1>

<p>In my quest to easily make available all the new command lines I learned at HackerYou I'm putting some of the basic workflows here.</p>  

<p>You will use <a href="http://github.com">GitHub</a> to host our version-controlled projects.</p>

<p><strong>$ pwd</strong>The present working directory is the folder that contains all your project files.</p>


<h2>Connecting to a New or Existing Repository</h2>

<h3>Cloning an Existing Repo</h3>
<strong>$ git clone https://github.com/gitName/fileName</strong>
<p>This will create a directory called 'fileName', initializes a .git directory inside and pulls down all the data from that repo.</p>


<h3>Initializing a Repo in an Existing Directory</h3>
<p><strong>$git init</strong> within the existing project's directory.</p>

<h2>Updating Changes to Repo</h2>

<p><strong>git add -A</strong>Add all new, modified and deleted files</p>
<p><strong>git commit -m "a useful commit message here"</strong>Commit your changes and updates to take the snapshot of your project. For your first commit, it’s common for your message to be “initial commit”.</p>
<p><strong>git status</strong>You can use this command at any step to check the status.</p>
<p><strong>git push origin master</strong>Note that all these steps are still happening locally on your computer. Push the code to your github repository.</p>
