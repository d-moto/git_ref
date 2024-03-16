## git command list

## 目次
- [git_config](#git_config)

## git_config
### gitにユーザ名をグローバルに設定する。
```
$ git config --global user.name "Silvers.Rayleigh"
```
### gitにユーザのメールアドレスをグローバルに設定する。
```
$ git config --global user.email "silvers.rayleigh@gee-mail.com"
```
### gitのデフォルトエディタをVScodeに設定する。
```
$ git config --global core.editor "code --wait"
```
### 現在のgitの設定をリスト表示する。
```
$ git config --list
```

```
$ cat ~/.gitconfig
$ git init
$ git add <file name>
$ git add .
$ git commit -m "<comment>"
$ git commit
$ git branch -m <branch name>
$ git remote add origin git@github.com:<username>/git-branch-name.git
$ git push origin main
$ git push -u origin main
$ git push
$ git clone git@github.com:<username>/git-branch-name.git
$ git branch
$ git branch -m <now branch name> <new branch name>
$ git branch -m <new branch name>
$ git branch -M <the branch name you want to forcebly change>
$ git switch <branch name>
$ git merge <sub branch name>
$ git status
$ git diff
$ git diff --cached
$ git log
$ git log --oneline
$ git branch
$ git branch -a
$ git branch -r
$ git branch -a = git branch + git branch -r
$ git branch --merged
$ git branch -d <the branch you want to delete>
$ git branch -D <the branch you want to forcibly delete>
$ git fetch <remote repository name> <remote branch name>
$ git fetch origin main
$ git fetch
$ git cherry-pick <commit hash>
$ git cherry-pick <commit hash>..<commit hash>
$ git cherry-pick --abort
$ git switch -c <new branch name> <commit hash>
$ git restore <file name>
$ git restore .
$ git commit --amend -m "commit msg"
$ git commit --amend
$ git reset HEAD
$ git reset
$ git reset -- <file name>
$ git reset --soft HEAD^
$ git reset --mixed HEAD
$ git reset --hard HEAD^
$ git log
$ git log --oneline
$ git log --graph --oneline
$ git log --graph --all --oneline
$ git log --pretty=format:"%h %s"
```
