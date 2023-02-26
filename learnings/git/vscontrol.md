# Version Control of Git
This doc is my learnings based on the course ["Version Control of Git"](https://www.coursera.org/learn/version-control-with-git/home/) on Coursera.

## Set up connection with the remote git repsitories
    Usually set up ssh connection with the remote git repositories.
    1. Generate a new ssh key on your local machine.
```
        $ ssh-keygen -t ed25519 -C "your_email@example.com"
```
    2. Add the new ssh key to your gitHub account
    3. Testing your ssh connection

     Refer to [Connectiong to github with ssh](https://www.coursera.org/learn/version-control-with-git/home/) on GitHub Docs.

## Clone a repository
    1. Get the ssh project link from the GitHub.
      ![Figure 1 GitHub Repository SSH Link](images/repos_ssh_link.png)  

    2. Run "git clone" on the local machine
       `$ git clone git@github.com:wowosky/projecta.git` 

       The password of your ssh key will be asked during the cmd run.

    3. A project directory same as the remote repository will be created in your local machine.

    