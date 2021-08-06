what is git?
Answer:-
Git is a free and open source distributed version control system designed to handle everything from small to very large with speed and efficiency.

Git is a software for tracking changes in any set of files , usually used for coordinating work among programmers developing source code during software development.

Linus Torvalds, the creater of Linux, created Git in 2005.

what is git hub?
Answer:-
Git hub is a web-based platform used for version control.

Github is a website for developers and programmers colaborately work on coded.

The primary benifits of Github is its version control system, which allows for seemless collaboration with compromising the integrity of the original project.

Git commands:-
1.Git config
git config -global user.name "name"
git config -global user.email "email"

The use of git config is that it sets the author name and email address respectively to be used with the commits.

2.Git clone
git clone [url]

The command is used to obtain a repository from an existing URL

Git add
git add [file]
example:-
git add github.md
This command adds a file to the staging area.

Git status
This command check the status lists all the files that have to be committed

Git commit
git commit -m "created guthub.md"
This command records the file permanently in the version history and here -m specifies a message.

Git push
git push origin sandeep@work
This command sends the committed changes of master branch to your remote repository.

Git rm
This command deletes the file from the working directory 

Git pull
git pull [Repository link]
This command fetches and merges changes on the remote server to you working directory.

Git branch
git branch --list
This command provides the list of branch is their.

Git branch -d [branch name]
This command deletes the branch

Git checkout
git checkout [branch name]
This command is used to switch from one branch to another.

Git checkout -b [branch name]
This command created a new branch and also switches to it.
