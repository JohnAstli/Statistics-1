# Statistics

## Create a directory. cd into it
## Initialize the git
```
git init
```
## Initialize your git information
```
git config user.name "your_name_goes_here"  
git config user.email "your_email_goes_here"
```
## Add the origin
```
git remote add origin https://github.com/georzaza/Statistics
```
## Download the latest origin 
This will download everything from the git. (will create folders etc)
```
git pull origin master
```
## do your changes or add new files or even subfolders with files on your working directory and then
## Add the files you want to upload
```
git add .                   --> adds every change (files, subfolders with files)
git add path_of_file        --> adds only specific file or files
```
## Add a message that will accompany these files
This is useful for version control (e.g. roll back to a previous version of a file)
```
git commit -m "The_message_of_the_commit"
```
## Upload the files you selected with the previous command
```
git push -u origin master
```

Hint: Maybe create a batch file to skip through some of these commads?
Create a start_git.bat (or name it as you want) 
Create a folder
cd into it.
copy the start_git.bat inside the folder
run it
then run the remaining commands manually (git add, git commit, git push)

start_git.bat may contain e.g.:
```
                git init
                git config user.name "your_name_goes_here"
                git config user.email "your_email_goes_here"
                git remote add origin https://github.com/georzaza/Statistics
                git pull origin master
```
