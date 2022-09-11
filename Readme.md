### Save change

- Stage your changes ( Selet the files / changes which are to be saved )

```
#To stage all changes
git add .

#To stage a perticular chage
git add <filepath> #git add src/app.js

#To unstage changes
git reset <filepath> #use . to unstage all changes
```

- Check working tree ( To check files staged / unstaged / commited ).

```
git status #Green(staged)/Red (Unstaged)/Other (commited)
```

- Commit your changes ( To save staged changes )

```
git commit -m <commit message> #git commit -m "Feat: Create web push notification"
```

- Check the commit log ( To check the commit history ).

```
git log
```