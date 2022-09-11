### Work in different feature

- Create new [branch](https://www.atlassian.com/git/tutorials/using-branches) ( To create a independent copy of the project )

```
#create new branch
git branch <newbranchname> #git branch feat/status/push-notification

#delete a branch
git branch -D <branchname>

```

- [Checkout](https://www.atlassian.com/git/tutorials/using-branches/git-checkout) to a branch ( For changing to perticular branch ).

```
#create and checkout to new branch
git checkout -b <newbranchname>

#For changing a perticular branch
git checkout <branchname>
```

### Branch naming convention

- Add main action type as base keyword (feat, fix, wip)

```
git branch feat/home/nav
```

- Add reset of the details as keyword (separate them with '-' or '/')

```
git branch feat/status/push-notification
```

- You can also use workboard card name as branch name
