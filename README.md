
# Git Basic(Commonders)

```
* git init 
* git git add -m "Some text here"
* git push 
* git clone url
* git pull origin master
```

# check branch status
```
* git status
* git checkout branchName

```


# git remote  add subbranch or remote branch 
```
* git remote add origin repoName
```

# git merge master to branch
```
* git checkout master
* git pull
* git checkout dev (othere branch)
* git rebase master
* git push --force # force required if you've already pushed
```

# git Log
```
* git log -2
* git log -i author="auther name"
* git log --oneline 
* git log --grep="text"
* git log -i -g"text here"
```

# git stash

* git stash save "text here"
* git stash list
* git stash drop 
* git stash pop
* git stash clean
