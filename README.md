# This is a readme file.

## creating a branch 
creates a develop branch and check it out
```shell
git checkout -b develop
```

## view branches
the branch with * denotes the current active branch
view the current active branch 
```shell
git branch 
```

## merge branches
navigate to the destination branch fx. if you want to merge to
main branch move to main branch first with `git checkout main` and
complete `git merge develop`
```shell
git merge <source_branch>