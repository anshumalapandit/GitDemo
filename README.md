# Project Overview
This repository contains two initial files transferred from my local development environment (VS Code) to GitHub. The purpose of this exercise is to demonstrate the correct use of Git and GitHub for version control.
# Steps to Transfer Files from Local Repository (VS Code) to GitHub
# ...
# 1. Initialize the Local Repository
First, I initialized the local folder as a Git repository, which allows Git to track changes:
git init
# 2. Stage Files for Commit
I added the files to the staging area. This prepares the files to be committed:
git add .
The . symbol stages all files in the current directory.
# 3. Commit the Staged Files
Next, I committed the staged files with a meaningful message. Each commit acts as a snapshot of the project:
git commit -m "Initial commit with two empty files"
# 4. Create a Remote Repository on GitHub
After that, I created a new repository on GitHub and copied its URL to connect it with my local repository.
# 5. Connect Local Repository to GitHub
I linked my local Git repository to the new GitHub repository using the following command:
git remote add origin <repository-url>
# 6. Push Local Changes to GitHub
Finally, I pushed my local commits to GitHub, making the files available remotely:
git push -u origin main
The -u flag sets the remote repository (origin) and branch (main) as the default for future pushes.
# 7. Confirm the Transfer
Verify that the files have been transferred successfully by checking the GitHub repository. The files should now be visible online.
