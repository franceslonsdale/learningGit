## This is me trying to learn git 😅 🎓
Follow this tutorial if you feel like you need to learn how to use github for beginners ❗


# Locally 🏠

Firstly you can either use git bash or put it in your terminal in my example I'm using the vs code terminal

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

## How to link to your repository on Github 🔗
To connect your locally stored code to the remote repository, this will make all your files from your local code to appear in the GitHub Repo!
**$ git remote add origin *remote_repo_url***   
**$ git push -u origin master**
To connect your locally stored code to the remote repository, this will make all your files from your local code to appear in the GitHub Repo!

## Contributing to other open-source projects on GitHub 🤝
This is for when we want to contribute to another open-source project on GitHub which we haven't been added to as a contributor.
Here are the following steps:
1. In your terminal use **$ git clone *projects_url***
2. Make any changes you'd like to
3. To push changes to remote fork **$ git push origin *branch_used***
4. Then on Github if you click on the branch youj used at the top, you can then create a pull request to pull in the remote changes and merge them intp the master/main branch

## How to contribute to a project when you have limit access
When collaberating online you may not have access rights to push and pull as you please to the repo which is understandable when you think about it! They don't know you are it provides a layer or protection for their code! However it's not all bad news as there is a very easy way to still contribute despite this which involves forking.

### How to fork
https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project - reference/ make summary
To fork we need to follow the instructions:
1. Click fork in the repo of choice <br> ![image](https://github.com/franceslonsdale/learningGit/assets/147734355/b4c30c00-a05f-498b-82e2-3bdb4efc75cb)
2. 

### Why fork
may have already done this one ****

# Updating changes ♻️
To make the change use **git add .** and then **git commit -m"*message for commit*** to lock in your changes 🔒. This will then commit the changes to the current branch. If you are on a side branch use **git pull *master branch name*** which updates you with the new changes from the main branch you may be behind on then go on main branch. The use **git push *name of main branch you want to push it to*** to send your changes to the *main* branch 💌 and use **git merge *branch name made changes on*** to confirm your merge and then it should have made the changes on GitHub webpage 💯
## Pushing and pulling
I need to describe what pushing and pulling does just so I have some point of reference



