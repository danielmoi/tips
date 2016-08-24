# GIT tips

> *160824*

## Checkout last checked-out branch
```
git checkout -
```

## Assume file is unchanged
```
git update-index --assume-unchanged <file-name>
```

## Get a list of all files marked `--assume-unchanged`
```
git ls-files -v | grep '^[[:lower:]]'
```

## Rebasing
```
git checkout develop
git pull --rebase
git checkout my-branch
git rebase develop
git push origin my-branch
```
