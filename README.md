# Exercise-Git-Learning
Step-by-Step Project Guide.

## Setting Up a GitHub Repository: 

1. Open your terminal.
2. Clone the repositories to your computer.
3. Navigate to Your Local Repository Folder: "cd ./{your repositories folder name}".
<<<<<<< HEAD
4. Open file (for example: README.md) in VScode and change the content.
5. Use "git status" to see if changes not staged for commit. You will see (with red colored): modified:   README.md.
=======
4. Open file in VScode and change the content.
5. Use "git status" to see if changes not staged for commit. You will see (with red colored): modified:   {your edited file}.
>>>>>>> fb7d51d (README.md)
6. Use "git add {your edited file}" to update what will be committed.
7. Then, use "git status" again. You will see (with green colored): modified:   {your edited file}.
8. After this, Changes to be committed. Use "git commit -m {your edited file}".
9. Now we can push it to our Github account using "git push origin main" (from origin folder on your computer to the main of the repositories).

## Steps to update your local repository with the latest changes from the remote repository:

1. Navigate to Your Local Repository Folder: "cd ./{your repositories folder name}".
2. Pull the Latest Changes: "git pull origin main".
3. Understanding the Result.
