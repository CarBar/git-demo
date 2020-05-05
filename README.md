# Git Demo README

## Commands

### git init

Create a new repository in the current directory. This is only done once per repository and is not needed when contributing to an established repository.

### git clone

Make a local copy of a remote repository to work with it. A repository is only needed to be cloned one time.

### git branch

The `git branch` command can be used to view branches that exist in a repository. The `-a` switch will allow you to view both remote and local branches. This command can also be used to create and delete branches as desired. Though creating branches is simple to do with [checkout](#git-checkout).

### git status

Check the status of your git repository. This provides information about current branch, content changes both staged and not.

![git status](img/git-status.png?raw=true "VisualStudio GIT settings")

### git push

Push the branch to **remote**, along with necessary commits and objects. If the branch does not exist on the remote you will be presented with a command to create the remote branch and push the local branch to the new remote branch.

![git push new branch](img/git-push-new-branch.png?raw=true "git push new branch")

### git pull

Fetch remote copy of current branch and immediately apply commits on the remote into the local copy.

### git fetch

Retrieve all changes in the remote repository. Fetch will pull the changes locally but not apply commits to the local copy.

![git branch behind HEAD](img/git-branch-behind-HEAD.png?raw=true "git branch behind HEAD")

### git commit

Create a new commit containing the staged file changes.
