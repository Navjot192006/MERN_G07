# MERN_G07
This is repository for G07

1..10 | ForEach-Object { $folder = "day_{0:D2}" -f $_ mkdir $folder "## $folder" | Out-File "$folder/README.md" }


1. git init
   -----> Initialize a new Git repository

2. git clone <repository-url>
   -----> Copy an existing GitHub repository to your computer

3. git status
   -----> Show the current status of files (modified, new, deleted)

4. git add .
   -----> Stage all changes for the next commit

5. git add <filename>
   -----> Stage only the specified file

6. git commit -m "message"
   -----> Save the staged changes with a commit message

7. git push
   -----> Upload your committed changes to GitHub

8. git pull
   -----> Download the latest changes from GitHub and merge them

9. git fetch
   -----> Download the latest changes without merging

10. git log
    -----> Show the complete commit history

11. git log --oneline
    -----> Show commit history in one line per commit

12. git branch
    -----> List all local branches

13. git branch <branch-name>
    -----> Create a new branch

14. git checkout <branch-name>
    -----> Switch to another branch

15. git checkout -b <branch-name>
    -----> Create a new branch and switch to it

16. git switch <branch-name>
    -----> Switch to another branch (new command)

17. git switch -c <branch-name>
    -----> Create and switch to a new branch

18. git merge <branch-name>
    -----> Merge the specified branch into the current branch

19. git remote -v
    -----> Show the connected GitHub repository URLs

20. git remote add origin <repository-url>
    -----> Connect your local project to a GitHub repository

21. git remote remove origin
    -----> Remove the connected GitHub repository

22. git remote set-url origin <new-url>
    -----> Change the GitHub repository URL

23. git restore <filename>
    -----> Undo changes made to a file

24. git restore .
    -----> Undo all unstaged changes

25. git restore --staged <filename>
    -----> Remove a file from the staging area

26. git rm <filename>
    -----> Delete a file from Git and your project

27. git mv <old-name> <new-name>
    -----> Rename or move a file

28. git diff
    -----> Show the differences between changes

29. git stash
    -----> Temporarily save uncommitted changes

30. git stash pop
    -----> Restore the most recently stashed changes

31. git reset --soft HEAD~1
    -----> Undo the last commit but keep the changes

32. git reset --hard HEAD~1
    -----> Undo the last commit and delete the changes

33. git config --global user.name "Your Name"
    -----> Set your Git username

34. git config --global user.email "your@email.com"
    -----> Set your Git email address

35. git config --list
    -----> Display all Git configuration settings
