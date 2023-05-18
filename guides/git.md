# Git Command Line Guide

The Git command line interface provides full control and flexibility for managing your local repositories and interacting with remote repositories. It requires familiarity with basic Git commands, such as git clone, git add, git commit, and git push. This option is suitable for developers comfortable working with the command line.

You can find detailed instructions on setting up git in the documentation available at [https://docs.github.com/en/get-started/quickstart/set-up-git](https://docs.github.com/en/get-started/quickstart/set-up-git)

## 🚀 Start Contributing
[Step 1: Fork this repository](#fork-this-repository)  
[Step 2: Clone this repository](#clone-this-repository)  
[Step 3: Create a branch](#create-a-branch)  
[Step 4: Make your changes](#make-your-changes)  
[Step 5: Stage your changes](#stage-your-changes)  
[Step 6: Commit your changes](#commit-your-changes)  
[Step 7: Push your changes to GitHub](#push-your-changes-to-github)  
[Step 8: Submit a pull request](#submit-a-pull-request) 

## Fork this repository

👉🏻 Click on the "Fork" button on the GitHub repository page 
then click Create a new Fork.

![Fork Repository](../assets/fork.png)

## Clone this repository

👉🏻 Open your Command line and execute the following command:

```
git clone https://github.com/<your-username>/OpenSourceJumpstart.git
```

## Create a branch

👉🏻 Navigate into your local repository using the following command:
```
cd OpenSourceJumpstart
```

👉🏻 Create a branch by executing the following command:
```
git checkout -b <your-username>-contribution
```

## Make your changes

👉🏻 Open CONTRIBUTORS.md in your code editor then add the following:
```
- [Your Name](https://github.com/<your-username>)
```

## Stage your changes

👉🏻 Stage your changes by executing the following command:
```
git add Contributors.md
```


## Commit your changes

👉🏻 Commit your changes by executing the following command:
```
git commit -m "<Your-Name> Contribution"
```

## Push your changes to GitHub

👉🏻 Push your changes to Github by executing the following command: 

```
git push -u origin <your-username>-contribution
```


## Submit a pull request

👉🏻 After pushing your branch to your forked repository, go to the original repository's GitHub page and click on "New pull request".

![Pull Request](../assets/pull.png)

🎉 Congratulations on successfully contributing to the project!





