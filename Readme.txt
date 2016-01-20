*****Readme******
Following are the list of commands in git

1. To initialize a project use >> git init <project-name>
The above line will help to create a folder called .git and relevant git files

2. This command >> git status
- provides which branch you are currently on
- what files have changed
- what files are not tracked
- hints on what to do next

3. git add .
- this command will add all the folders / files in this directory to track in the staging area

4. git add Readme.txt
- this command will add the specific file name to track

5. git rm --cached Test1.txt
- this command will remove the Test1.txt file from cached / unstage

6. git commit -m "initial commit"
- this command will commit the project files

7 git log
- this command will display the status of commit

8.before commiting any files, it needs to go from staging area and for that we need to do (git add) command
  and then (git commit -m "message") command

9. git diff
- this command will provide the differences in all the files

10. git diff --cached
- this command will provide the difference in cached / staged files

11. git log --oneline
- will provide list of all commits with one line messages

12.  Shift zz
- short cut to come out of the bash

13. git commit -a -m "your message"
- will stage and commit in one go

14. git status -s
- will provide what has been modified (list of file names only)
   