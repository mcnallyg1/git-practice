# git-practice

[GitHub Repo](https://github.com/mcnallyg1/git-practice)

Open the command line 

Start by cloning the repo locally:
```
git clone https://github.com/mcnallyg1/git-practice.git
```
change the dir to the git repo
```
cd git-practice/
```

Create a new branch
```
git checkout -b <branch_name>
```

**Add your name to names.txt**

See your changes made  in names.txt
```
git diff
```

This pulls the latest changes from GitHub repo 
```
git pull origin master
```

**fix any conflicts**
[Resolving conflicts in WebStorm](https://www.jetbrains.com/help/webstorm/resolving-conflicts.html)

add the edited names.txt to the staging area
```
git add names.txt
```

saves your changes your branch
```
git commit -m “your meassage”
```

shows your commit in the history of the branch
```
git log
```

Will push your saved changes to the GitHub repo
```
git push origin <branch_name>
```

[Create a pull request](https://github.com/mcnallyg1/git-practice/compare)

pick the base to be **master**
Pick compare to be **<branch_name>**
Click **Create pull request**

After it is created it will be reviewed to be merged

Delete your branch after your pull request has been approved
```
git branch -d <branch_name>
```