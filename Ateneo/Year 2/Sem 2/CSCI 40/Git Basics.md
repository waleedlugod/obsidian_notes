# Version Control Basics
keep track of file change, software version
## Terminology
repository: storage for files
commit: a saved change; when there is something to be committed
branch: path of development
main branch: production release; source of truth

# Git
version control system (VCS)
key features:
* distributed repositories
* fast branching
* staging area
git: VCS software
github: remote repository
## Distributed repository
version control operations are done locally
every developer has their own local copy
## Fast branching
features branches: branches used to test new idea while keeping main branch stable
staging area: choose which files to commit

# Getting Started with Git
`git help everyday`

# Working with Branches
like a linked list
tip of branch: latest commit
HEAD: pointer to the commit being currently looked at; typically the latest commit
`git checkout <commit id>`: look at a commit

branches should e created when:
* new features
* fixing existing code

`branch new_feature && git merge master`: master merge into new_feature
`git checkout master && git merge new_feature`: new_feature into master

# Working with Remotes
`git clone <URL|local repository name> <optional destination directory>`
`git log --simplify-by-decoration --decorate --all --oneline`: list branches

when cloning, only active branch is checked out
other branches are just tracked

`git checkout <branch>`: checkout tracking branch and make a branch out of it
## Remotes
references to the original repository
references can be to a local or remote location

`git remote -v show`: show URL of remote
remote URLs show 2 URLs
* fetch URL
* push URL
## Pushing changes
`git push <remote name> <local branch>`
* proper permissions must be needed
* permissions are granted by the remote owner
`git push origin master`

`git push --set-upstream origin new_branch`: pushes current branch and setup upstream tracking
## Pulling code
updating local code with changes from remote
combination of `git fetch` and `git merge`

`git fetch`: retrieves references
`git merge FETCH_HEAD`: combine changes
* FETCH_HEAD is tip of remote
## Merge conflicts
look for markers
* between `<<<< HEAD` and `=====` are local changes
* after `=====` are remote changes
remove markers and edit to desired code to resolve

# Working with History
`git log --parents --oneline`: see all commits and their parents
`git log --oneline <file> <file2>`: commits that affect specific files

3 commit IDs is a merge
## Search contents
`git log --grep=<serach term>`
`git grep <search term>`
## Commit difference
`git log --patch <hash>^..<hash>`: difference between commit and its parent
* `git log --patch HEAD^..HEAD`: same but for HEAD
## Visualize branches
`git log --graph --decorate --oneline --all`

# Rebasing
take all changes from one branch and replay them on a different branch

the log of a rebased branch looks like a linear history

```
git checkout experiment
git rebase main
git checkout main
git merge experiment
```
## Rebase vs Merge
Rebasing replays changes in the order they were introduced
story of how the project was made

Merge takes the endpoints of branches and merges them together
record of what actually happened
# Warnings
**do not rebase commits that exist outside your repository and that people may have based work on**
rebasing abandons exising commits and creates similar ones