# .github CHEATSHEET
- Download git from https://git-scm.com/ and install git
- Run GitBash, this opens a command promp window for git

- Create a repository within the organization or choose an existing repository.
###In GitBash:
To clone an existing repository into your local drive & create edits
```
  $ cd /c/Users/YourName/folder/folder/folder....... # Navigate  using cd to your desired Project Folder
  $ git clone https://Atlantic-Engineering-Group/targetrepository.git   # clone your target repository, you can copy paste the url
  $ git remote -v       # check the remote (i.e. what repository is git pointing toward?)
  $ remote add origin https://.............git      # if the remote was not pointing toward the correct repository, you can add that url here.
  $ git remote -v      # check the remote again
  $ git pull       # pull all the files from the existing repository. If you already have this folder created, then it just updates existing files. (i.e. "reconcile")
  # now you can make any changes you want to the code
  $ git add .  # add all files to temporary
  $ git commit -m "comment"  # commit changes to temporary, you can use a fork
  $ git push origin main  # send the changes back to github
```
To Edit an Existing Repository (repo exists in GitHub and you have already cloned it into your folder):
```
  $ cd /c/Users/YourName/folder/folder..... #Navigate to your desired project folder.
  $ git remote set-url origin [repo-url]
  $ git add .             # You may have to perform a git pull to get all updates.
  $ git commit -m "Comment"
  $ git push origin main
  
```
You can use the following method if you mess up on your $git add .
```
$ git reset  
# This command can reset $ git add, and $ git commit
```
To get rid of those pesky .xml documents (created by the PYT toolboxes):
  use a .gitignore.txt file
  
```
# Ignore all .xml files
*.xml
```
