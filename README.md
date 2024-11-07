# Exercise-Git-Learning
I edited it using VScode.

## Steps to update files with the terminal:

1. Clone the repositories to your computer.
2. Use "cd ./{your repositories folder name}"
3. Open file in VScode and change the content.
4. Use "git status" to see if changes not staged for commit. You will see(with red colored): modified:   README.md.
5. Use "git add {your edited file}" to update what will be committed.
6. Then, use "git status" again. You will see(with green colored): modified:   README.md.
7. After this, Changes to be committed. Use "git commit -m {your edited file}".
8. Now we can push it to our Github account using "git push origin main" (from origin folder on your computer to the main of the repositories).