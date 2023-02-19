```bash
# git stash 
alias gss="git stash save"
alias gsa="git stash apply"
alias gsl="git stash list"

# git status
alias gs="git status"
# git branch
alias gb="git branch"

# git diff 
alias gdiff="git diff"  # 比较工作区与暂存区
alias gdifflocal="git diff --cached" # 比较暂存区和本地仓库

# git reset
alias greset="git reset --mixed"
alias greseth="git reset --hard"
alias gresets="git reset --soft"
# git revert
alias grevert="git revert"
# git clean
alias gclean="git clean -n"
alias gcleanf="git clean -f"
alias gcleanfd="git clean -df"


# push pull fetch merge rebase checkout add commit cherry-pick
# git checkout
alias gch="git checkout"
alias gchb="git checkout -b"
# git rebase
alias gr="git rebase"
alias gri="git rebase -i"
# git fetch
alias gf="git fetch"
# git pull
alias gpl="git pull"
# git push
alias gp="git push"
alias gpom="git push origin master"
alias gpsom="git push --set-upstream origin master"
# git merge
alias gm="git merge"
alias gmm="git merge master"
alias gmabort="git merge --abort"
# git commit
alias gcm="git commit -m"
# git add
alias ga="git add"
# git cherry-pick
alias gcp="git cherry-pick"
# git tag
alias gtl="git tag -l"
alias gtdel="git tag -d"
alias gt="git tag"
alias gtp="git push origin | git tag | head -n 1" # 推送第一个标签

# git log show
alias gl="git log --graph --pretty=oneline --abbrev-commit"
alias greflog="git reflog"
```