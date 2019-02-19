#Adding existing project to git

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
