What is Github-
GitHub is a web-based version-control and collaboration platform for software developers.

Use for-
Git is used to store the source code for a project and track the complete history of all changes to that code. It allows developers to collaborate on a project more effectively by providing tools for managing possibly conflicting changes from multiple developers.GitHub allows developers to change, adapt and improve software from its public repositories for free, but it charges for private repositories, offering various paid plans. Each public or private repository contains all of a project's files, as well as each file's revision history. Repositories can have multiple collaborators and can be either public or private. 

Git commands-
1. gitclone-
	$ git clone <https://url-of-the-repository> :
	The git clone command is used to download the source code from a remote repository.
2. Gitbranch-
	$ git branch <branch-name> :
	Branch is one of the most important functionalities of Git. This allows teams to work on the same code base in parallel. 
	You can use this command to create a new branch, view existing branches, or delete a branch.
	$ git branch - command to view all branches.
	$ git branch -d <branch-name> : command to delete branch.^[[D^[[D^[[D^[[3. Git Checkout-
	$ git checkout <branch-name> :
	This will automatically switch you to the branch name you mentioned in the command.
	$ git checkout -b <branch-name>  :                                 
	this command works exactly same
4. Git Add-
	$ git add <file-name> :
	This command will add only a single file to your next commit.
	$ git add -A :
	This command will add all the files to which changes were made.
	Your changes will be recorded only when you commit them.
5. Git Commit-
	$ git commit -a :
	This will commit all the changes in the directory you’re working in. Once this command is run, you’ll be prompted to enter a commit message.
	$ git commit -am “<commit-message>" :   
	you can enter the commit message in the command itself and skip the additional step where you’ll be prompted to enter the commit message.
6. Git push-
	$ git push <remote> <branch-name> :
	It’s important to remember that git push command will upload only the changes you’ve committed.
7. Git pull-
	$ git pull <remote> :
	The git pull command allows you to fetch all the changes that your teammates pushed and automatically merge them into your local repo.
8. Git diff-
	$ git diff branch1..branch2 :
	This will compare two branches.
	$ git diff branch1 branch2 ./path/to/file.txt :
	Compare file from two branches.
9. Git stash-
	$ git stash save “<stash-message>” :
	This will stash your changes with the message you entered.
10. Git status-
	$ git status :
	This can give you information such as
		* Your current branch
		* Whether your current branch is up to date
		* If there’s anything in the branch that needs to be committed, pushed, or pulled.
		* If you have any files that are either staged or not staged.
		* And if you have any files that are created, modified, or deleted.
11. Git log-
	$ git log :
	This displays the entire commit history. If your commit history is large, it’ll show only a portion of it and you can hit [space] to scroll or type q to quit.
12. Git merge-
	Imagine you’re currently in your feature branch called feature1 and you’re ready to merge it to the develop branch.
	$ git checkout develop : We must first switch to the develop branch using the checkout command.

	$ git pull : Before merging, you must make sure that you update your local develop branch. 
	We do this by running the pull command.

	$ git merge feature1 : We do this by using the git merge command followed by the branch name that we want to merge into our current branch.
13. Git init -
	$ git init :
	The git init command is usually the first command you’d run in any new project that is not already a Git repository .
14. Installing git-
	$ sudo apt install git-all :
15. git version-
	$ git  --version : checks which version is installed in pc
16. git config -
	$ git config --globle user.name "git user name" :configer username
	$ git config --globle user.email "Email" : set email.
