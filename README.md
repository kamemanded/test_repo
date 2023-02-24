# Git testing

Here is a summary of the provided code along with step-by-step instructions:

```bash
# Create a new file called README.md and add a heading "Git" to it:
touch README.md && echo "# Git" >> README.md

# Check that the file README.md has been created:
ls

# Open the README.md file in the Vim text editor:
vim README.md

# Add a line to the README.md file with the heading "Git testing"
# Save and close the file in Vim

# Initialize a new Git repository in the current directory:
git init

# Check the status of the repository and see that there are no commits yet:
git status

# Add the README.md file to the staging area:
git add README.md

# Commit the changes with a message:
git commit -m "First commit for git test"

# Check the status again and see that there are no changes:
git status

# Add a remote repository to push to:
git remote add origin https://github.com/kamemanded/test_repo.git

# Rename the default "master" branch to "main":
git branch -M main

# Push the committed changes to the remote repository:
git push -u origin main
