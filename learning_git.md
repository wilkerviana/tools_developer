Learning Git&Github
===================
Start a git local repository
-------------------

* Open terminal and choice your directory for start repository

* Set your user and email git for the commits identified
```
git config --global user.name "Bruce Wayne"
git config --global user.email "bruce@ciawayne.com"
git config --global core.editor subl //for set text editor sublime text
```
*  Come'on! Start local repository
```
git init
```
* Check your repository status
```
git status
```
* Track file/folder to stage area
```
git add ~file/folder~
```
* Ready for commit. Let's go!
```
git commit -m "My file was committed!"
```
* For commit all files tracked, use:
```
git commit -am "All my files were committed!"
```
* See your commit logs
```
git log
```
* Verify changes in your modified area
```
git diff
git diff --name-only // for verify file name modified
``` 
* If you want keep your changes without commit, use:
```
git stash
```
* For recovery your stash
```
git stash apply
```

Start a git remote repository
----------------------