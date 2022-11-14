# Git-commands

#### List local branches

``` git branch ```

#### List remote branches

``` git branch -r```

#### List all branches

``` git branch -a```

#### Check out to a remote branch in local 

``` git checkout -b LocalName origin/remotebranchname```

#### List existing remotes
``` git remote -v```

#### Change the 'origin' remote's URL
```  git remote set-url origin https://github.com/user/reponame.git```

#### Add upstream
``` git remote add upstream “forked repo” ```
Eg: git remote add upstream https://github.com/username/reponame.git

#### Remove upstream 
``` git remote remove upstream```

#### Show remote 

``` 
git remote show origin
git remote show upstream
```

#### Delete local branch
```
git branch -d
git branch -D (force delete)
```

#### Delete remote branch

``` git push origin --delete develop```

#### To fetch an upstream branch, not in remote origin 
If there is a branch(new) in upstream not listed in origin.
``` Eg git remote show origin```
> does not list demo

```  git remote show upstream```
> lists demo

```
git fetch upstream demo: demo

git status

git push demo

```

#### Add additional remote
``` git remote add remote-name https://github.com/remote-name/repo.git```
```
git remote -v
remote-name  https://github.com/remote-name/repo.git (fetch)
remote-name  https://github.com/remote-name/repo.git (push)

git fetch --all
```
