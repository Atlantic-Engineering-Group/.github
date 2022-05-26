# .github CHEATSHEET
```
Download git from https://git-scm.com/ and install git
Run GitBash, this opens a command promp window for git

Create a repository within the organization or choose an existing repository.
In GitBash:
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

To Edit an Existing Repository:
  $ cd /c/Users/YourName/folder/folder..... #Navigate to your desired project folder.
  $ git remote set-url origin [repo-url]
  $ git add .
  $ git commit -m "Comment"
  $ git push origin main
```
