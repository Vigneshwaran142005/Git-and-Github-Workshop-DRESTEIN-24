# Git-and-Github-Workshop-DRESTEIN-24
NAME:M S VIGNESHWARAN 
REGISTER NUMBER : 212223050059 
DEPARTMENT :B.E EEE  
YEAR :  2nd year
1. Setup and Initialize: 
mkdir git-workshop      # Create the directory
cd git-workshop         # Navigate into the directory

2. Initialize a Git Repository:
 git init

3. Create and Modify Files:
  echo "Hello, Git Workshop!" > hello.txt
   
4. Check the Status of Your Repository: 
  git status

5.Stage and Commit Changes
 git add hello.txt
 git commit -m "Add hello.txt with welcome message"

6.Branching
 git branch update-content
 git checkout update-content

7. Make Changes on the Branch:
 echo "This is a simple Git assignment." >> hello.txt
 echo This is a simple Git assignment. >> hello.txt
 git add hello.txt
 git commit -m "Update hello.txt with additional message"
 echo "This is a simple Git assignment." >> hello.txt
 git add hello.txt
 git commit -m "Update hello.txt with additional message"

8.Merge changes
 git checkout main
 git switch main
 git merge update-content
 git checkout main
 git switch main
 git merge update-content

9.View Commit History
 git log
 git log --oneline
 git log --graph --oneline
 git log hello.txt

10.Undo and Reset
 git checkout -- hello.txt
 git restore hello.txt
 git reset --soft <commit-hash>
 git reset --mixed <commit-hash>
 git reset --hard <commit-hash>
 git log
 git reset --hard abc123
 git checkout -- hello.txt
 git restore hello.txt

11.Push to a remote Repository 
 git remote add origin <remote-url>
 git remote add origin https://github.com/username/repository.git
 git push origin main
 git remote add origin <remote-url>
 git push origin main

 


   
   
