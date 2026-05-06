# Cmds!

```
git init                                    # turn this folder into a repo (initializes)
git add <fileName>                          # adds one file to the stage 
git add -A                                  # Add all changed, created, and deleted files to stage
git commit -m '<msg>'                       # commit whats staged
git branch                                  # list of branches and whats checkout with a *
git checkout -b <branchName>                # Creates new local branch (if not there)

git merge <otherBranchName>                 # Merges other branch to the one currently checked out
git checkout <branchName>                   # Change to the branch

git log                                     # Show commit history
clear                                       # clean up ui of terminal

git remote add <origin> <url>               # add a new remote , connect to github
git push origin <branchName>                # Sync up to github, any branch
git pull origin <branchName>                # Sync down from github to local and merging

git reset --hard <id or tag>                # go back in time to id/tag
git tag -a '<ver>' -m "<msg>'               # tag the current commit of the current branch
git push origin --tags                      # tags push seperate
```
