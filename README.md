# Learn git and github Basic
Learning GitHub is a great way to improve your skills as a developer, collaborate with other developers on open source projects.

## Architecture
![Architecture](Architecture.png)

## Where i start to learn git and github
# Steps 
- A repository is a place where you can store and manage your code. 
- You can create a repository on GitHub and upload your code to it. GitHub provides an easy-to-use interface for managing your repository and collaborating with others.

# Use this command for upload project on it
- Open Git Bash: Open Git Bash on your computer.
- Navigate to your project directory: Use the cd command to navigate to your project's root directory.
-- cd path/to/your/project

- Initialize Git (if you haven't already): Initialize a new Git repository in your project directory by running:
-- git init

- Add your files: Add all your project files to the staging area:
-- git add .

- Commit your changes: Commit the added files with a descriptive message:
-- git commit -m "Initial commit"
  
- Create a new repository on GitHub: Go to GitHub and create a new repository.Do not initialize it with a README, .gitignore, or license.

- Add the remote repository: Add the URL of the GitHub repository you just created as a remote repository:
-- git remote add origin https://github.com/yourusername/yourrepository.git
 // Replace https://github.com/yourusername/yourrepository.git with the actual URL of your GitHub repository.

- Push your project to GitHub: Push your local repository to GitHub:
-- git push -u origin master
or try
-- git pull --rebase origin master



