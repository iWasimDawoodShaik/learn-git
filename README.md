## Practicing git commands

```
git status
git init
git add .
git commit -m "first commit mesage"
git log
git log --oneline
git add <file_name>
git commit -m "add <file_name> to the codebase"
git status
git diff <hash_1> <hash_2>
git branch
git branch <new_branch>
git switch <new_branch>
git checkout <new_branch>
git switch -c <new_branch>
git checkout -b <new_branch>
git merge <new_branch> # get <new_branch> code to main
git status
git rebase main # write this from the <new_branch> to clean the commit timeline
git stash
git stash pop
git branch -d <new_branch>
git branch -M main
git branch
git remote -v
git remote add <remote_name> <remote_url>
git push <remote_name> <branch_name>
git push -u <remote_name> <branch_name>
git push
```