# Commands

Removing git branches recursively

`git branch | grep -v "master" | xargs git branch -D`

Git squash

`git rebase -i HEAD~3` where 3 is the number of commits you wish to squash, usually the whole thing

Pull master into your current branch

`git pull --rebase origin master`
