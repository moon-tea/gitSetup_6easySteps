gitSetup_6easySteps
===================
##### git hub repo set up in 6 easy steps

### You can create a new repo in 3 steps
------------------
###### sets up the necessary git files
```
$ git init
```
###### connect to your created repository
```
$ git remote add origin https://github.com/[UserName]/[myRepository].git
```
###### do an initial pull
```
$ git pull origin master
```

### After set up, you can update a repo in 3 steps
----------------------
###### adds all the files
```
$ git add --all
```
###### appends a message
```
$ git commit -m "message"
```
###### now you can push
> Note, you will need username and password

```
$ git push -u origin master
```

### Branching is easy too
-------------------------
```
$ git branch BranchName
$ git checkout BranchName
$ git add --all
$ git commit -m "message"
$ git push origin BranchName
```
