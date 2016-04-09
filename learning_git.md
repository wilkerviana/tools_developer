Learning Git&Github
===================
Start a git local repository
-------------------

1. Open terminal and choice your directory for start repository

2. Set your user and email git for the commits identified
```
git config --global user.name "Bruce Wayne"
git config --global user.email "bruce@ciawayne.com"
git config --global core.editor subl //for set text editor sublime text
```
3.  Come'on! Start local repository
```
git init
```
4. Check your repository status
```
git status
```
5. Track file/folder to stage area
```
git add ~file/folder~
```
6. Ready for commit. Let's go!
```
git commit -m "My file was committed!"
```
7. For commit all files tracked, use:
```
git commit -am "All my files were committed!"
```
8. See your commit logs
```
git log
```
9. Verify changes for commit
```
git diff or git diff --name -only
``` 
10. If you want keep your changes without commit, use:
```
git stash
```
11. For recovery your stash
```
git stash apply
```

Start a git remote repository
----------------------