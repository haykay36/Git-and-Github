# Version Control

Version control system, also known as source control is the practice of tracking and managing changes to files or set of files over time. The most common type is a centralized VCS, which uses a server to store all the versions of a file.Developers can check out a file from the server, make changes,and check the file back in. The server then stores the new version of the file.

# Git and Github

**git** is a popular version control system that is used to:

- Track code changes
- Track who made changes
- Coding collaborations

**Git** can be downloaded using the URL [Git URL](http://git-scm.com/downloads)

**Github** is a code hosting platform for version control and collaborations.
It lets you and other developers work together on projects from anywhere.
It can be accessed by registering account at [Github URL](www.github.com)

# Difference between git and github

Git is a version control system that allows developers to track changes in
their code. GitHub is a web-based hosting service for git repositories. In simple terms, you can use git
without Github, but you cannot use GitHub without Git.

# Three alternative GitHub Apps

These are alternative apps that can be used in place of github

- GitBucket
- Gitea
- BeansTalk

# Difference between git fetch and git pull

The key difference between git fetch and pull is that git pull copies
changes from a remote repository directly into your working directory,
while git fetch does not.
The git fetch command only copies changes into your local Git repo. The
git pull command does both.

# git rebase and the command for it

The git rebase command allows you to easily change a series of commits,
modifying the history of your repository. You can reorder, edit, or squash
commits together. Typically, you would use git rebase to: Edit previous
commit messages.
Typically, you would use git rebase to:

- Edit previous commit messages
- Combine multiple commits into one
- Delete or revert commits that are no longer necessary

**To rebase the last few commits in your current branch, you can enter the following command in your shell:**
`git rebase --interactive HEAD~7`

**To rebase all the commits between another branch and the current branch state, you can enter the following command in your shell (either the command prompt for Windows, or the terminal for Mac and Linux):**
`git rebase 'interactive OTHER-BRANCH-NAME`

# git cherry-pick and the command for it

git cherry-pick in git means choosing a commit from one branch and applying it to another branch.
This is in contrast with other ways such as merge and rebases which normally apply
many commits into another branch. git cherry-pick is just like rebasing, an advanced concept and also a powerful command. It is mainly used if you don’t want to merge the whole branch and you want some of the commits.

**The command for Cherry-pick is as follows:**
`git cherry-pick "commit-hash`
