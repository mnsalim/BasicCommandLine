<<<<<<< HEAD
Basic Commands for different purposes 
=======
# BasicCommandLine
1. - h : typing -h after any commands show the available paprameter

## Commands for git and github
1. Clone online repository to local machine
   git clone <-url of github repository>
2. print out remote repository links (need to type it inside a local repository)
   git remote -v
4. Commit: set of saved repository changes. Commit nver lost and has a hashkey. 
     git add . (. means add all the files)
     git add file1.txt file3.txt
     git commit -m "Your comment" (just put any meaningful comment)
     
6. staging: if any file under stagged we can commit.
     git add add one or more file to staging
       echo staged > stagedFile.txt (your file name)
       echo unstagged > unStaggedFile.txt
     git reset <-file name> is used to unstagged any file
     git status give us an overview of untracked file
8. branches: A branch is simply a series of commits that can be manipulated independently. git maintain a master branch by default and you can create other branch any time of commit.
     To see all branches type: git branch
     Create new branch: git branch <-branch name> (* shows that we are working on that branch)s
     switch branch: git checkout <-branch name>
10. checking
      To show logs: git log
          To exit from logs, press q
      To show stagged and untracked files: git status
      To show details about specific commit: git show <commit hash value which can be retrived from git log command.
        git show --name-only <-commit hash value>
      To show all changes happened in the project in any branch: git 
12. git config--> to update your user name and email for resolving "Author identity unknown" error
    git config --global user.name "You Name"
    git config --global user.email johndoe@example.com
13. git push: send commits to central repository
    git pull: retrieve commits from central repository
    git clone <-url link> <-new repository name> (if you want to clone same project twice and give different name to the new clone porject)
15. Undowing changes: two ways
       revert command create a new commit that undoes the changes of a certain commit
          git revert 1d268a3c86fb50a6addea4e36b7f711665c841ef (your cmmit hash)
       reset command reset up to porvided hash
          git reset <-hash >
          git reset --soft <-hash> (disregards subsequet commits but keeps the changes they have introduced, this is default)
          git reset --hard <-hash>
          
17. 



## Commands for Windows command line
1. clear screen: cls
2. show all directory: dir
3. Change directory: cd
4. write something in a file:echo <something> > <file name.text>
5. 
>>>>>>> 62a8183d0886febe0e704b43ad9e23044b2b618c
