### Installation

- Download [git](https://git-scm.com/downloads) ( windows/mac/Linux ).
- Install the git with default setup ( After installtion check git bash in your device ).

```
git --version #In CMD / Terminal ( Bash )
```

### Configure git remote data

- Add your remote [configuaration](https://linuxize.com/post/how-to-configure-git-username-and-email/) global / local scope

```
#Global scope
git config --global user.name <username> #git config --global user.name "afeef"
git config --global user.email <email>

#Local scope
git config user.name <username>
git config user.email <email>
```

- Confirm config details

```
git config --list #show all config datas
```
