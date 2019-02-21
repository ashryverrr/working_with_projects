# working_with_projects
Simple commands in using git and other programming language

How to Use Github
If copying existing project from Git
1. Create repository online
2. Copy the link of the repository
3. Open CMD and open local source folder
4. Run command git clone "link"

If uploading existing project on your computer
1. Initialize git git init
2. Run command git add .
3. Run git commit -m "Message"
4. Run git remote add origin Add Link
5. Run git push -u origin master

Commands in uploading changes 
1. Git status - show all changes in the repository
2. Git add -filename - add file to commit
3. Git commit -m "Message" - save changes
4. Git push - Upload the changes online
5. Git pull - pull changes online

Updating remote origin repository
1. Show your current remote origin, git remote show origin
2. Remove current origin, git remote rm origin
3. git remote add origin _path_to_new_origin_

Python
Working with project requirements using Pip
- pip install -r requirements.txt
- pip freeze > requirements.txt
