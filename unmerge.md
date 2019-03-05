# If you hit MERGE after creating your pull request:

## On Github:
  * Go to your list of commits
    * Find your github repository (www.github.com/cisc3130/ASSIGNMENT_NAME/YOUR_USERNAME)
    * Click the "Code" tab (the first one)
    * Click the "# commits" tag (# will be how many commits you've pushed)
  * Make sure you're in the master branch
  * Find the last good commit. On the master branch, this should be the last commit from rivlev (your changes should be confined to the hw branch)
  * On the right, there is a 7-character code. Copy it by clicking the clipboard next to it
  
## Next, on your computer:
  * Open up terminal/command prompt. Navigate to your git repository. Make sure you're in the master branch
  * Type ```git reset --hard <PASTE COMMIT CODE>```
  * Type ```git push -f origin master```
