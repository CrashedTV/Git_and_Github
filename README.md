# Git_and_Github
We talk about the Git and GitHub in this file.

Git
    Version Control System which helps to track change in the code.

GitHub
    Allows developer to store and manage their codes.


If we start the project by making repository in GitHub first then we perform the following actions.

To create new Repository

    1. Go to GitHub.com. 
    2. Click on "+" button.
    3. Select "New repository".
    4. Enter the Repository Name.
    5. Enter the Repository Description.(Optional)
    6. Select the Repository Visibility.(Public or Private)
        // Private - will be seen by only collaborators and owner.
        // Public - will be seen by everyone.
    7. Add a README file.
        // You can write about the projects.
    8. Click on "Create repository" button.

README file can be updated by clicking on edit icon.
After editing write the message that you have updated.
Then click on "Commit changes" button.

Setting up Git<br>

    To check the version of Git 

        git -v or git --version

    If Git is not installed then install Git from the below URL:
        
        URL : https://git-scm.com/downloads
        // Choose Git according to your OS.

Configuring Git
    Configuring Git means that in which GitHub account we are making changes.

    Commands to Configure
    
        1. git config --global user.name "GitHub_Username"
        2. git config --global user.email "GitHub_Email"


Remote : GitHub <br>
Local : Laptop or PC 

Clone <br>
    The repository made in GitHub wilol be cloned on the local machine.

    Command to Clone
        
        git clone <-https link->
        // Replace the link with the repository link.

Status <br>
    Used to check the status of the repository.

    Command to check status
        
        git status

    Types of status
        1. Unmodified
            No changes made

        2. Modified
            Changes made in local machine but not committed to the Remote Repository.
        
        3. Staged
            Changes made in local machine & added and ready to commit to the Remote Repository.

        4.Untracked
            New file is added to the Local Machine but not added to the Remote Repository.

Add & Commit

    add - adds new or changed files in Local Machine to the Git Staging area.
        Command
            git add <file_name> // for individual file
            git add . // for all files in the directory

    commit - adds a snapshot of the files in the Git Staging area to the Local Repository.
        Command
            git commit -m "commit message" // for individual file
            git commit -m "commit message" . // for all files in the directory

Push
    Pushes the changes made in the Local Repository to the Remote Repository.

    Command
        git push origin main


