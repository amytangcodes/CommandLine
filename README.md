<h1>Command Line Cheat Sheet for Beginners</h1>

<p>In my quest to easily make available all the new command lines I learned at HackerYou I'm putting some of the basic workflows here.</p>  

<p>You will use <a href="http://github.com">GitHub</a> to host our version-controlled projects.</p>

<p><strong>$ pwd</strong>The present working directory is the folder that contains all your project files.</p>


<h3>Connecting to a New or Existing Repository</h3>

<h5>Cloning an Existing Repo</h5>
<strong>$ git clone https://github.com/gitName/fileName</strong>
<p>This will create a directory called 'fileName', initializes a .git directory inside and pulls down all the data from that repo.</p>


<h5>Initializing a Repo in an Existing Directory</h5>
<p><strong>$git init</strong> within the existing project's directory.</p>

<h3>Updating Changes to Repo</h3>

<p><strong>git add -A</strong> Add all new, modified and deleted files</p>
<p><strong>git commit -m "a useful commit message here"</strong> Commit your changes and updates to take the snapshot of your project. For your first commit, it’s common for your message to be “initial commit”.</p>
<p><strong>git status</strong> You can use this command at any step to check the status.</p>
<p><strong>git push origin master</strong> sNote that all these steps are still happening locally on your computer. Push the code to your github repository.</p>

<h3>Pushing Changed Repo Versions to Our Repo Version</h3>

<p><strong>git remote -v</strong> Associating remote and our repo versions</p>
<p><strong>git remote add upstream https://{remote repo}</strong> Upstream means the original version</p>
<p><strong>git remote -v</strong> Check the repo version on GH you're working with</p>
<p><strong>git remote add origin https://{github-address}</strong> If ^ version pulls nothing, then pull your repo</p>
<p><strong>git pull upstream master</strong></p>
<p><strong>git log</strong></p>

<h3>Create a Site from GitHub/ Syncing Branches</h3>
<p><strong>git checkout -b gh-pages</strong> Create and switch to the new gh-pages branch - git check out: switches branches | -b: also creates a new branch at the same time</p>
<p><strong>git branch</strong> Switches between branches</p>
<p><strong>git checkout master</strong> Switch to master to update</p>
<p><strong>git rebase gh-pages</strong> Updates changes in gh-pages into master</p>			
<p><strong>git push origin gh-pages</strong> Can update gh-pages while in master</p>
<p><strong>http://username.github.io/repository.</strong> Site location</p>