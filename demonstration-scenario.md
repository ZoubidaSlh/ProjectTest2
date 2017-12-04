# GitHub Demonstration

### Create Project on GitHub

1. You can create a project on GitHub ...
2. Add collaborators

### Setup local repositories

🖥 Machine 1
```
$ mkdir zoubida-demo 
$ cd zoubida-demo
$ git clone https://github.com/ZoubidaSlh/ProjectTest2.git
$ code ProjectTest2 // open project on VS Code editor 
```
🖥 Machine 2
```
$ mkdir narjis-demo
$ cd narjis-demo
$ git clone https://github.com/ZoubidaSlh/ProjectTest2.git
$ atom ProjectTest2 // open project on Atom editor 
```
### Edit files & commit

🖥 Machine 1 : Editing file & pushing changes to remote repo

After editing the file README.md 
```
$ git add .
$ git commit -m "Add parag 2"
$ git push origin master

```
🖥 Machine 2 : Getting last changes from remote repo

```
$ git pull origin master

```
### Editing & Resolving conflicts ⚠️

🖥 Machine 1 : Editing file README.md & pushing changes to remote repo

```
$ git add .
$ git commit -m "Add title 3 & parag 3"
$ git push origin master

```

🖥 Machine 2 : Editing file REAME.md & pushing changes to remote repo

```
$ git add .
$ git commit -m "Add parag 4"
$ git push origin master

$ 
``` 

