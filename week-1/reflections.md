#1.1 Think About Time Reflection

**what I have learned?**
-the Pomodoro technique. I like the idea most of all because it seems to be a simple way for maintaining the focus (I have a problem with that)
-the importance of protecting myself of external interactions
-the habit of integrating a recap after a task/release/sprint. It´s very usefull to evaluate what I working fine and what I can improve
-the idea of begining "small" when I want to do something or integrate a new habit. 
what is time-boxing and how can I use it?
Time-boxing is fixing a task/goal/objectif and fixing a limited time for doing it and after this fixed time stop even if the goal is not achieved and review.
I think I am going to use it all the time on Phase 0: for pear-pearing sessions and GPS but also for my personal work at DBC and outside and my personal goals (see next item for more details).

**What I am currently doing and is it working?**
-I have an Agile-inspired way of listing the task I need/want to do. I use the Trello tool for a visual support. I divide my tasks into 4 boxes: sandbox, icebox, "backlog" and "sprint". My sprints duration is 1 week.
-I  also have a week-timetable (Excel) which integrates health, work and family time
The Trello works pretty well but what I need to improve is that I have to learn to estimate the time I am going to need for accomplishing a goal more accuratly. I saw this point specifically is part of the Pomodoro technique, so I purshased a Pomodoro book and I will try to learn more about it.
Also what is not working is the contingency management. When I have a big unexpected that comes, I loose control on y schedules.

**What is my plan for Phase 0 and how to emply what I have learned?**
I will integrate my new learnings by iterations in order to test if the changes work:
My first iteration will be next week (week2) and will include :
-keep my existing Trello backlog
-keep my existing week-timetable
-split my existing Trello "backlog" into 25 minutes tasks
-focus on one task at a time, review and then take a 5 minutes break
-avoid all interruptions during the 25 timebox
-talking to my family and explain them my new organisation in order for them to understand and not feel rejected
-review my new management technique after week 2 and try to improve what needs to be improved
-repeat an iteration every week untill I feel satisfied whith my new time management technique






#1.2 The Command Line Reflection
1-What is a shell? What is "bash?"

A shell is a macro processor that executes commands.
Bash is the shell for GNU
2-What was the most challenging for you in going through this material?
-This material was really time consuming for me. It took me more than 5 hours to accomplish the release.
3-Were you able to successfully use all of the commands?
yes
4-In your opinion, what are the most important commands and arguments to know?
the commands used for the compilation of the files and generation of the executables. In this case "ruby" for Ruby and "cc" for C.
5-Can you remember what each of the following does of the top of your head? Write what each does.
-pwd displays the path of the current directory
-ls displays a list of the files and the directories in the present directory
-mv moves a file to another directory
-cd change the directory
-../ goes to the root
-touch creates a 0-byte file
-mkdir creates a directory
-less pager that displays the content of a file page by page
-rmdir deletes a directory
-rm deletes a file
-help I do not know on the top of my head. Maybe the same thing than "man"?




#1.4 Forking and cloning Reflection
**If you were going to write instructions for a new person on how to create a new repo, fork a repo, and clone a repo, what would they be? Why would you fork a repository as opposed to create a new one?**

*on your browser
-create a Github account in github.com and choose a USERNAME
-to create a new repository, go to github.com/[USERNAME], then click on "Repositories", then click on the "New" button.
-to fork a repository, go to an existing Github repository
-click on the fork button on the top-right of the interface. You will be redirected to your local coppy of this repository (github.com/[USERNAME]/[NAME OF THE FORKED REPOSITORY])
-copy the fork adress on "clone url"
*locally into your command line
-go to the directory where you want to create your clone
-type "git clone [THE CLONE URL YOU HAVE COPIED BEFORE]" on you command line
-type "ls" to see if the clone has been created

**What struggles did you have setting up git and GitHub? What did you learn in the process?**
I work in windows with a Virtual Machine, so this adds extra steps to the process oand as I was very late when I started my windows setups on the week 0, I did not take the time I neede to understand how the Virtual Machine worked and the relationship beetween the differente directories. 
In the process I had to go back to the tasks I performed on week 0 for my setup and understood that during those setups I´ve already created a clone locally of the phase-0-box repository. It's silly but I was pretty happy when I realized that little detail even if I don´t understand yet all the details of the setup I have performed on week 0 and I fell frustrated with that.


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


#1.6 Your website Part 1 Reflection

**Paste a link to your [USERNAME].github.io repository.**
https://github.com/vagurtomejia/vagurtomejia.github.io

**Explain how to create a repository on GitHub and clone the repository to your local computer to a non-technical person.**
-create an new account in github.com with the user name USER_NAME
- go to github.com/[USER_NAME]
-click into the "+" symbol besides you profile picture
-enter your repository name, choose it as public, choose a type of licence
-click the "Create repository" button
-copy the CLONE URL displayed in the right side of your repository
-in your command line type "git  clone CLONE_URL" where CLONE_URL is the previously copied url

**Describe what open source means.**
Open source is a computer program in which the source code is available to the public for use, modification and distribution.

**What do you think about Open Source? Does it make you nervous or protective? Does it feel like utopia?**
I think the Open Source movement is an example for all the people. In our society we are taught to compete and to be selfish. The Open Source brings a tottaly new paradigm based on collaboration, sharing and working for the common good.

Assess the importance of using licenses.
When we use a licence whe explicitly choose a way of sharing and protecting our work.

What concepts were solidified in the challenge? Did you have any "aha" moments? What did you struggle with?
It was very usefull for me to repeat once again the complete workflow for making changes to a repository. No aha moments this time :) No struggles neither.

Did you find any resources on your own that helped you better understand a topic? If so, please list it.
I didn´t look for other ressources sadly. I'm already way behind on my week work.
