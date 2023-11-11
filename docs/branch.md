# Branching

Two **workflows:**

- main branch + dev branch---keep them forever, and merge dev to main when this is ready
- main branch + topic branch---when work is done at topic branch, merge it to main then delete the topic branch

## Create a new branch

```r
git checkout -b new_branch
# or
git switch -c new_branch
```

## Get a new branch from remote

```r
git fetch origin
git checkout -b new_branch origin/new_branch
```

## merge a branch to main

```r
git checkout main
git merge a_branch
```

## delete a local branch

```r
git checkout main
git branch -d local_branch
```

## delete a remote branch

```r
git fetch origin
git push --delete origin remote_branch
```

