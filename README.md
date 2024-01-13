# Git-commands-for-github
push , pull , commit, remote, create branch,etc all commands 


### Install git on your computer.
### Go to files directory and open git bash by right clicking.

# Upload files on github :-

<ul>
  <li>Follow commands :- 
    <ul>
      <li><b>git config --global user.email "Your Email"</b></li>
      <li><b>git config --global user.name "Your Name"</b></li>
      <li><b>git init</b>			 //make project as a git project</li>
      <li><b>git add [filename] or -A</b>	//add file on git if you want to add all file</li>
      <li><b>git status</b>			//check status if file add or not on git</li>
      <li><b>git commit -m "any msg"	</b>	//create a snapshot or copy of all file</li>
      <li><b>git remote add origin repoLink </b>	//link between git and hosting platform such as github <br> //repolink means create a repository  on github and copy repository  link</li>
      <li><b>git push origin branch_name </b>		//upload means put all files on github</li>
    </ul>
  </li>
</ul>

# Download or Fetch all files of repository  from githhub :- 

<ul>
  <li>
    <b>git clone repolink</b>//connect between user to github repository  link and download
  </li>
</ul>

# Upload only updation of files :-
<ul>
<li><b>git add [filename] or -A</b>	//add file on git if you want to add all file</li>
      <li><b>git status</b>			//check status if file add or not on git</li>
      <li><b>git commit -m "change msg"	</b>	//create a snapshot or copy of all file</li>
      <li><b>git remote add origin repoLink </b>	//link between git and hosting platform such as github <br> //repolink means create a repository  on github and copy repository  link</li>
      <li><b>git push origin branch_name </b>		//upload means put all files on github</li>
</ul>

# Download or Fetch updation :-
<ul>
  <li>
    <b>git pull origin master</b>
  </li>
  <li>
    <b>OR</b>
  </li>
  <li>
    <b>git pull origin main</b>
  </li>
</ul>

# Create Branch :-
<ul>
  <li><b>git branch</b>  				//to view all branches</li>
  <li><b>git branch branchName</b> 			//create new branch eg. git branch yash</li>
  <li><b>git checkout branchName</b>			//switch one brach to another branch</li>
</ul>

# Merge Braches :-
<ul>
  <li>
    <b>git merge branchName</b> 
  </li>
</ul>

# Remove git initialization :-
<ul>
  <li>
    <b>rm -rf .git</b> 
  </li>
</ul>
