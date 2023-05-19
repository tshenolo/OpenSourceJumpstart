# GitHub CLI Guide

GitHub CLI is a command-line tool specifically designed for GitHub. It provides an intuitive way to interact with GitHub repositories and perform various tasks, such as creating pull requests, reviewing code, and managing issues. GitHub CLI simplifies the workflow by eliminating the need to switch between the command line and the GitHub web interface.


You can find detailed instructions on setting up Github CLI in the documentation available at [https://cli.github.com/](https://cli.github.com/)

IMPORTANT: Prior to starting your contributions, please authenticate your GitHub account by opening your command line and executing the following command:

```
gh auth login
```

By running this command, you will be guided through the authentication process to link your command line interface with your GitHub account.

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

👉🏻 Open your Command line and execute the following command to fork the repository:

```
gh repo fork tshenolo/OpenSourceJumpstart
```

## Clone this repository

👉🏻 Clone the repository by executing the following command:

```
gh repo clone <your-username>/OpenSourceJumpstart
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
git add CONTRIBUTORS.md
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

👉🏻 After pushing your branch to your forked repository execute the following command to submit a pull request

```
gh pr create
```

🎉 Congratulations on successfully contributing to the project!















