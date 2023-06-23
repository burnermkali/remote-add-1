# remote-add-1
how to remote add a repository from your terminal
--------

#!/bin/bash

# Change to the directory where you want to initialize the Git repository
cd /path/to/your/directory

# Initialize a new Git repository
git init

# Add all files in the current directory to the repository
git add .

# Commit the changes with a commit message
git commit -m "Initial commit"

# Add the remote repository URL
git remote add origin <remote_repository_url>

# Push the code to the remote repository
git push -u origin master
