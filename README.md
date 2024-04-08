## This is me trying to learn git 😅
Follow this tutorial if you feel like you need to learn how to use github for beginners ❗


# Locally 🏠

**$ git init**
initiallises new git hub repository

### Making git ignore
I'd recommend installing zombie package for gitignore on vs code
then in the search bar at the top press Ctrl, Shift, p to get this icon > and then search gitignore and press Add gitignore file. Then it'll let you search again and type in
Node.gitignore and click this and all the files to ignore it will do

## Branching

**$ git branch** shows the current branch you are working on
**$ git checkout -b feature** creates a new branch feature and switches to
**$ git checkout feature** switches you to feature branch if already existing
**$ git checkout -** switches you back to main branch

### Why we use branching
Branching allows for collaberation as each person can work on a seperate branch and then commit their changes and then they can be merged onto the same file.

This is great however this can cause merge conflicts, as you could imagine some of the code in the side branch may conflict that already in the main branch however once you merge these together the branch 
can resolve this by looking at each conflict within the code and deciding whether you want to keep the original or keep the new change as given by the side branch.

Essentially if we were working on a new branch let's name it feature and we committed changes, these changes won't be seen on the main branch. Then from the master branch we can use
**$ git merge feature**. 
If say the feature branch is multiple commits ahead of the main branch we can merge them all at once but we have to use **$ git merge -- feature squash**


# Github Remotely 🏘️

## How to link to your repository on Github
To connect your locally stored code to the remote repository, this will make all your files from your local code to appear in the GitHub Repo!
**$ git remote add origin *remote_repo_url***   
**$ git push -u origin master**
To connect your locally stored code to the remote repository, this will make all your files from your local code to appear in the GitHub Repo!

## Contributing to other open-source projects on GitHub
This is for when we want to contribute to another open-source project on GitHub which we haven't been added to as a contributor.
Here are the following steps:
1. Fork the existing project
2. In your terminal use **$ git clone *projects_url***
3. Make any changes you'd like to
4. To push changes to remote fork **$ git push origin *branch_used***
5. Then on Github if you click on the branch youj used at the top, you can then create a pull request to pull in the remote changes and merge them intp the master/main branch
   
