# cheat-sheet
Git is a distributed version control system that helps developers track changes, collaborate on projects, and manage code versions efficiently. Here are some essential Git commands with examples:

Configuration and Setup

Before using Git, you need to configure your username and email:

git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
These commands set your username and email globally for all repositories
1
2
.

Initializing a Repository

To start a new Git repository, use:

git init
This command initializes a new Git repository in the current directory
1
2
.

Cloning a Repository

To clone an existing repository from a remote server, use:

git clone <repository_url>
This command copies the repository to your local machine
1
2
.

Basic Git Commands

Adding Files

To add a specific file to the staging area:

git add <file>
To add all modified and new files:

git add
These commands prepare files for the next commit
1
2
.

Committing Changes

To commit changes with a message:

git commit -m "Your commit message"
This command records the changes in the repository with a descriptive message
1
2
.

Checking Status

To check the status of your repository:

git status
This command shows the current state, including tracked and untracked files
1
2
.

Viewing Differences

To see changes between the working directory and the staging area:

git diff
This command displays the differences
1
2
.

Branching and Merging

Creating and Switching Branches

To create a new branch:

git branch <branch-name>
To switch to a branch:

git checkout <branch-name>
To create and switch to a new branch:

git checkout -b <new-branch-name>
These commands help manage different versions of your project
1
2
.

Merging Branches

To merge a branch into the current branch:

git merge <branch>
This command integrates changes from one branch into another
1
2
.

Working with Remote Repositories

Fetching and Pulling

To fetch changes from a remote repository:

git fetch
To fetch and merge changes:

git pull
These commands update your local repository with changes from the remote repository
1
2
.

Pushing Changes

To push local commits to a remote repository:

git push
This command uploads your changes to the remote repository
1
2
.

Managing History

Viewing Commit History

To view the commit history:

git log
This command shows the commit history of the current branch
1
2
.

Reverting Changes

To revert a specific commit:

git revert <commit>
