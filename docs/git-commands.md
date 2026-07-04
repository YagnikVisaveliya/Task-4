# Git Commands Reference

## Setup
​```bash
git init                        # initialize repo
git clone <url>                 # clone remote repo
git remote add origin <url>     # link remote
​```

## Branching
​```bash
git branch                      # list branches
git checkout -b <branch>        # create + switch branch
git checkout <branch>           # switch branch
git branch -d <branch>          # delete branch
​```

## Daily Workflow
​```bash
git status                      # check changes
git add .                       # stage all changes
git commit -m "message"         # commit changes
git push origin <branch>        # push to remote
git pull origin <branch>        # pull latest
​```

## Merging
​```bash
git merge <branch>              # merge branch
git rebase <branch>             # rebase branch
git cherry-pick <commit>        # pick specific commit
​```

## Stash
​```bash
git stash                       # save uncommitted changes
git stash list                  # list stashes
git stash pop                   # restore latest stash
git stash drop                  # delete latest stash
​```

## Tags
​```bash
git tag                         # list tags
git tag -a v1.0.0 -m "msg"     # create annotated tag
git push origin v1.0.0          # push tag
git tag -d v1.0.0               # delete tag
​```

## Logs
​```bash
git log --oneline               # compact log
git log --oneline --graph       # visual branch graph
git diff                        # show unstaged changes
git diff --staged               # show staged changes
​```