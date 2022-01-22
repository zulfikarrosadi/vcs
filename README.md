# VCS
learn how to use git and github

#### git clone
adding '.' (period) at the end of git clone will clone the repo without creating new folder
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
the differences is when doing ```fetch``` we just getting the changes or update information about the file without getting the actuall file, and for ```pull``` is going to download the changes and merge it to our local repo
```
git pull origin
git fetch origin
```