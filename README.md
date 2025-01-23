Features:
Local Project Creation:
The script creates a new folder on your local machine with the specified project name. If the folder already exists, it skips this step.

Git Initialization:
Initializes a new Git repository in the created folder using the git init command.

GitHub Repository Creation:
Uses the GitHub API (via the PyGithub library) to create a new repository in your GitHub account. You can specify whether the repository should be public or private.

Adding a README.md File:
A basic README.md file is generated automatically in the local project folder. It includes the project name and description.

Committing and Pushing to GitHub:

The script stages all files (git add .) in the repository.
It creates an initial commit (git commit -m "Initial commit").
It sets the main branch as the default branch.
Links the local repository to the newly created GitHub repository using git remote add origin.
Pushes the changes to GitHub (git push -u origin main).
