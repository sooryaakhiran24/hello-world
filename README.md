# hello-world

### Steps to connect GitHub with Windows
1. Create a GitHub profile if you don’t have one.
2. Login into Windows laptop/PC
3. Download GIT using the link [Git for Windows](https://gitforwindows.org/), execute the file and follow the instructions in it.
4. After installation, open the command prompt and execute the command “git -v” to check the version is been shown.
5. Add the GitHub profile in the cmd using the below commands
    `git config --global user.name "<username>"`
    `git config --global user.email "<email address>"`
8. Initialize the git using the command 
    `git init`

![My GitHub Profile page](/assets/github_profile.png)

### Steps to clone the project and commit your changes to GitHub

1. Go into GitHub and create a repository 
2. Copy the repository URL for cloning the repository
3. Clone the project into the local system using the command 
    `git clone <URL>`
4. Go into the directory create a sample text file and save it.
5. Use `git status` to check the status of the git.
6. Add the files in the list using the command `git add .`, “.” represents to add all the files present in it.
7. Commit the changes using the command ` git commit -m “message” `.
8. Push the committed changes using the command `git push`
9. Check the GitHub repository whether the committed contents is been updated or not.

