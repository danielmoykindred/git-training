# Git Training
A basic practical guide on how to use git

## Branches
**TODO**

## Adding files to a commit

### Adding a specific file

`git add <path/to/file.ext>`

### Adding all files in current directory

`git add .`

## Creating a Commit
A commit is like a save state for the repository. All files are saved at that particular moment, and can be recalled at any time.

`git commit -m "Commit message describing the changes I made"`

## Pushing a Commit to the Remote Repository
Commits are only stored locally. In order for others to know about it, we need to push it to a centralized repository. GitHub is an example of a website that hosts repositories.

`git push`

## Pulling Changes Made by Others
Just like you, others are making changes to the repository at the same time as you. In order to bring in their changes into your local repository, we need to pull it from the centralized repository.

`git pull`

If we are on a development branch and we need to pull the most up-to-date `master` branch

`git pull origin master`

The keyword `origin` indicates that we want to pull from the centralized repository on GitHub. Techncially, this can be renamed, but the standardized word (and the default) is `origin`.

The keyword `master` indicates the branch we want to pull from. This will pull the master branch and all its changes into your current branch.
## Resolving a Conflict
