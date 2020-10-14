# Statistics

# Create a directory. cd into it (e.g. c:\users\admin\workspace)

\code {git init}        --> this will create a hidden directory named .git inside the folder you're working

git config user.name "your_name_goes_here"  

git config user.email "your_email_goes_here"

There is an option to make the above commands global-effective (meaning you will not have to type them each time). 
I think it's --global, google it. It's better to not config with this option in my opinion.

git remote add origin https://github.com/georzaza/Statistics    --> adds the origin  

git pull origin   --> pulls the origin files (always do that, as someone else might have changed the files)

// do your changes or add new files or even subfolders with files on your working directory

git add .                   --> adds every change (files, subfolders with files)
git add path_of_file        --> adds only specific file or files

git commit -m "The_message_of_the_commit"   --> Using this message we can track the changes later, so maybe include your name here also?

git push -u origin                          --> uploads the files you added with git add command and every file will have the message of git commit command.


Hint: Maybe create a batch file to skip through some of these commads?
Create a start_git.bat (or name it as you want) 
Create a folder
cd into it.
copy the start_git.bat inside the folder
run it
then run the remaining commands manually (git add, git commit, git push)
start_git.bat :
                git init
                git config user.name "your_name_goes_here"
                git config user.email "your_email_goes_here"
                git remote add origin https://github.com/georzaza/Statistics
                git pull origin
