## 9.6.2024 das ist ein Beispiel

# GIT = Version Control System

## Guide for GIT

Git is used to track changes in source code, revert to previous versions, create branches, and merge them.
GitHub is used for sharing these projects and collaborating with others.

## Git Commands

- **git init** creates a new git repository. It creates a .git directory in the specified directory and converts the existing directory into a Git repository.

- **git add** : Adds the specified file to the staging area. With "git add .", all files can be added to the repository at once.

- **git commit** -m "descriptive message": Saves changes in the staging area to the repository with a message. Always use present tense English.
  git status: Shows the status of files in the working directory and staging area.

- **git log**: Displays the commit history in the repository.
  git clone: Copies a repository from the specified URL (from GitHub) to the local computer.

- **git diff**: Shows differences between the working directory and the staging area or between two commits.

- **git branch**: Lists current branches or creates a new branch.

- **git checkout**: Switches to the specified branch.
  git checkout -b: Creates a new branch.
  git merge: Merges a specified branch into another branch.
  git remote add [name] [url]: Adds a new remote repository.
  git fetch: Retrieves the latest copies of all branches and commits from the remote repository to the local repository.
  git pull [remote] [branch]: Retrieves (almak) changes from a remote repository to the local repository and merges them. Performs fetch and merge at the same time.
  git push: Sends local changes to the remote repository.
  git reset: Removes the specified file from the staging area.
  git rm [file name]: Removes the specified file from the repository and the working directory.
  git stash: Temporarily stores changes in the working directory and cleans the working directory.
  git stash pop: Restores stored changes and removes them from the stash list.
  git tag [tag name]: Adds a tag to the specified commit.
  git remote -v: Lists remote repository connections for the Git repository. Shows both fetch and push URLs.
  git fetch [remote-name]: Retrieves data from the specified repository. If the name is not specified, it defaults to origin.

Commit: Indicates the version of our project.
Main: Indicates that we are in the newest commit area. This is the latest version of our project or code.
Git fetch and push manage data synchronization between the local and remote repositories.
Fetch: Downloads all changes from the Remote Repository to the local repository but does not alter the local working files, only displays the remote data.
Git clone copies the entire repository and clones it to the local computer. Through forking on GitHub, we can add a clone of someone else's repository to our own. Changes made do not reflect in the main project.
Someone can make local changes to another's project using Git clone and open a Push Request on GitHub. If the project owner likes the branch, they can Confirm Merge and add that area to their project.
