#1.5 Tracking changes Reflection
**How does tracking and adding changes make developers' lives easier?**
	by tracking and adding changes developers can avoid to mess-up their code and the one of their collaborators because it is always possible to go back to a working version if needed. They can also be informed of their collaborators work.
**What is a commit?**
		a commit is a saving point of our work 
**What are the best practices for commit messages?**
		best practices are to start whith a summary line (50 characters) of the changes, then leave a blanck line, then list the detail of the changes using present imperative formulations
**What does the HEAD^ argument mean? **
		the HEAD^ argument refers to the previous commit
**What are the 3 stages of a git change and how do you move a file from one stage to the other? **
		1-if we create a new file it will be listed as "untracked" 
		git add file_name will add the file into the repository
		2-then it will be listed as "changes to be commited"
		git commit file_name will commit the changes
		3-then it will be listed as "up to date"

**Write a handy cheatsheet of the commands you need to commit your changes? **
		pull origin master to retrieve the remote repository changes into the local
		checkout -b my_new_branch to create and go to a new branch

		add . (adds the changed files to the repository)
		commit -m "creates a handy cheatsheet to commit my changes" 
		merge 

**What is a pull request and how do you create and merge one? **
		a pull request submits my changes from local to remote version in order to validate my changes and merge them with the remote repository
		how:
		-push origin my_branch
		-then on Github:
		-pull requests
		-create a pull request
		-compare the chosen repositories
		-create pull request
		-merge
**Why are pull requests preferred when working with teams?**
		with a pull request my changes can be verified/tested by my coworkers before being added to the master branch
