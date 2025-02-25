# Learn git

## Learn to use help guides

```
git -h or git --help

git branch -h or git add -h or git clone -h
```

## Initialize git

```
# initialize git
git init
```

## Change or move the main branch from master to main

```
git branch -M main
```

## Track your first to files

```
git add learn-git.md
git add welcome.html

or

git add learn-git.md welcome.html

or

git add -A
```

## commit the welcome.html

```
git commit -m "added new welcome html file"
```

## see the changes

```
git log
```

### set a remote machine (github)

```
git remote add origin <url>
```

### set an upstream from your local branch to the main remote branch

```
git push -u origin main
```

### Once you do changed and need to commit again

```
git add welcome.html

git commit -m "update welcome.html"
```

### push the changes

```
git push
```
