# VCS
learn how to use git and github

adding '.' (period) at the end of git clone will clone the repo without creating new folder
```
git clone https://github.com/zulfikarrosadi/vcs.git .
```

connect your local repo to remote repo
```
git remote add origin https://github.com/zulfikarrosadi/vcs.git
```
> IMO, origin is just the alias or name to the link of remote repo,
> so when we push or fetch we dont have to type the link again


uploading changes to remote repo
```
git push origin <branch_name>
```

getting stuff from fetch
