1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.  
A:  git status

2. Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.  
A: git add hello-world.txt  
git commit -m “hello-world.txt is created”

3. Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.  
A: git diff README.md  

4. Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.  
A: git show abc123

5. Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.  
A: git log --oneline -n 3

6. Assuming that you are currently within a Git repository, write the command (or commands) that will check to see if the remote repository contains any new commits.  
A: git fetch  
git status