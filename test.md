# Adding existing project to git

1. Create a new repository on GitHub. Do NOT initialize the repo with a README

2. Change the current working directory to your local project in the terminal
``` 
$ git init 
```
	
3. 
``` 
$ git add . 
```

4. 
``` 
$ git commit -m 'First commit' 
```

5. Copy the remote repository URL from GitHub

``` 
$ git remote add origin *remote repository URL* 

$ git remote -v
```
6.
```
git push -u origin master
```



Remove pushed commits
https://stackoverflow.com/questions/6459080/how-can-i-undo-a-git-commit-locally-and-on-a-remote-after-git-push


Get remote branch locally
https://stackoverflow.com/questions/1783405/how-do-i-check-out-a-remote-git-branch
git checkout -b test <name of remote>/test

Stash
git stash - your modified tracked files and staged changes, saves it on a stack of unfinished changes that you can reapply at any time.
git stash apply stash@{2} - If you don’t specify a stash, Git assumes the most recent stash and tries to apply it
git stash pop - apply the stash and then immediately drop it from your stack.
