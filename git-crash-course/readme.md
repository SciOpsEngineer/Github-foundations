
# Cloning 
There are three ways to clone github repo

- 1. Via HTTPS
```sh
mkdir workspace/tmp
cd workspace/tmp

```

```sh
git clone https://github.com/JJDataAnalyst-viz/Github-foundations.git
```

- 2. Via SSH

```ssh
git clone git@github.com:JJDataAnalyst-viz/Github-foundations.git
```

- 3. Via GitHub CLI

```Github CLI
gh repo clone JJDataAnalyst-viz/Github-foundations
```
# Commits

```sh
git commit -am 'First commit'
```

# Branches

Create new branch 

```sh
git switch -c dev_branch
```

# Remotes

```sh
git remote add origin https://github.com/JJDataAnalyst-viz/Github-foundations.git

```
# Push
``` sh
git push --set-upstream origin main 
```


# Stashing

Stash before staging branch.
Then pop or apply stash in the same branch or other
```sh
git stash 
git stash list 
git stash save my-name
git stash apply
git stash pop

```
# Merging


```sh
git checkout dev
git merge main
```