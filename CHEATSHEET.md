## Clone

* With ssh key
```
exec ssh-agent bash
ssh-add ~/.ssh/my-githubkey

git clone git@github.com:microsat-dpad/git-demo.git
```

* Without ssh key
```
git clone https://github.com/microsat-dpad/git-demo.git
```

## Show modified files
```
git status
```

## Show commit logs
```
git log
``` 

## Commit Changes
```
git add .
git commit -m "Added awesome chunk of code"
git push -u origin master
```

## Pull Latest Code from Github
```
git pull origin master
```

## Create new branch
```
git branch -b feature-name
```

## Switch branch
```
git fetch
git checkout master         // to transfer to master branch
git checkout feature-name   // to transfer to feature-name branch
```

## Rebase master into feature-name branch
```
git fetch
git checkout feature-name
git rebase master
```

## Merge feature-name branch into master
```
git fetch
git checkout master
git merge feature-name
git push -u origin master
```
