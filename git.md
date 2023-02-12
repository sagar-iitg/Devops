
### Most Used

```
   git init


```


## How to use .gitignore

###  ignore file error.log
```
error.log
```

### ignore multiple .log file

```
 *.log
```


### ignore any directory/folder

```
dir/
```
### ignore only outter directory/folder

```
/dir/
```


### git ignore blank folder by default




```

git config --global user.email "enter your email id"
git config --list
git config --global core editor emacs
git config --global core editor vim
git config user.name
git config user.email
git status
git init

```

#### --a means all



```
 git add --a
 git add .
```

```
git commit -m "msg"
git log
git clone https://github.com/sagar-iitg/git-learning.git git-learning
```


#### comparing working directory to staging area

```
git diff 
```
#### comparing previous commit to current staging area(green color) --> modified
```
git diff --staged
```

### skipping staging area

```
 git commit -am "msg"
```



### How do I get the Git commit count?

```
git rev-list --count HEAD
git rev-list --count master 
```



### To get the commit count across all branches:

```
19. git rev-list --all --count 
20. git mv file.txt info.txt
21. git rm new1.txt
```




### if previously git is tracking file then command is to untrack file is:

```
git rm --cached file.txt
git rm --cached -f file.txt

```



### default branch is master


```


  git log
  git log -p
  git log -p -3
  git log --stat
  git log --pretty=oneline
  git log --pretty=short
  git log --pretty=full
  git log --since==2.days
  git log --pretty=format:"%h --%an"
  git log --pretty=format:"%h --%ae"

```



### unstaged file


```
git restore --staged <file>
git checkout -- <file>
git checkout -f
git remote  
git remote add origin git@github.com:sagar-iitg/git-learning.git
git remote -v

```





### git alias

```

 git config --global alias.st status 
 git config --global alias.last 'log -p -1'
 git config --global alias.unstage 'restore --staged --'
 git branch
 git config --global 
 git stash
 git stash pop
 git checkout -b f2


```



### delete loccal branches

```
 git branch -d f1

```




### delete remote branch
```

git push origin --delete f1
git push origin bugfix:mybugfix

```


### Branch Management




```


 git branch
* master
  develop
  system

git branch -v
```



### already merged branches
```
git branch --merged
```

### not already merged branches  

```
git branch --no-merged
git branch -d develop
git branch -D develop


```



## remove/clear git repository


```
rm -rf .git

```

