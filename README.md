# VCS
learn how to use git and github

### Small Team Workflow
1. Create branch from develop branch and call it like "feature-<describe fiture or ID>"
2. Work on that feature, commit if there any changes that should to commit
3. Test your feature
4. Merge into develop branch
5. Delete feature branch
6. Once enough features and / or fixes has been completed, prepare your release
7. Once release is tested and prepped, merge into master
8. Tag master branch commit with release number
9. Repeat

### Basic command

#### git clone
adding '.' (period) at the end of git clone will clone the repo without creating
new folder
```
git clone https://github.com/zulfikarrosadi/vcs.git .
```

#### git remote
connect your local repo to remote repo
```
git remote add origin https://github.com/zulfikarrosadi/vcs.git
```
> IMO, origin is just the alias or name to the link of remote repo,
> so when we push or fetch we dont have to type the link again


#### remote push
uploading changes to remote repo
```
git push origin <branch_name>
```

#### fetch and pull
the differences is when doing ```fetch``` we just getting the changes or update
information about the file without getting the actuall file, and for ```pull``` 
is going to download the changes and merge it to our local repo
```
git pull origin
git fetch origin
```

#### git tag
all recent commit will be tagged to this v0.1.0
```
git tag -a v0.1.0 -m "optional message"
git show tag v0.1.0
git push --tags origin master
```

#### git log
logging your changes with little sparkle
```
git log --oneline --decorate --graph --all
```