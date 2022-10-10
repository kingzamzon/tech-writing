## Introduction to GitHub

Introduction

Have you ever thought of going back to the changes to made last 2 days even after shutting down your laptop. Version control are tools that let you have different versions of your file. One of the popular version control is git.
There is need to know what was added last 2 days and who made the changes. And ease for collaboration. There where git comes n place.
There is no Github without git. so what is git. Git is a version control tool for tracking code changes, who changes codes e.tc now we want to make git accessible people outisde our intranetwork/ network. on the internet where Github comes in place. Take your git repository
global with GitHub.

## Prerequisites

- Have Git installed on your local machine. 
- Have Github Account.

## What is GitHub

Github is the largest host the source code in the world. It owned by Microsoft in 2018.

## Why GitHub

Github cause it houses all the popular tools raning from react to Linux kernel it has popularity that make is easy to reach with developers around the world.

## Git vs. GitHub

Git is a version control system. It is used to track changes on files, enable collaboration on files.

Github is a web based version of Git on the internet.

## Clone
Clone a repository is pulling down a full copy of repository to your local machine.

1. Navigate to the repository you want to clone, in this example we will use clone the [Linux kernel](https://github.com/torvalds/linux)
2. Click on the green <> code button.
3. Copy the url for the repository by clicking on the copy button ![Copy Button](/images/img2a.png) using one of the option HTTPS, SSH or GitHub CLI
   ![Copy drop down](/images/img2b.png)
4. Open Your Terminal
5. Type `git clone` and paste the link you copied in 3, press enter to start cloning.

![Clone Button](/images/img1.png)

## Pull request 

Pull Request is a way to contribute to repository on github. It is a mechanism for a developer to notify team members that they have completed a feature. 

1. Fork the repository, by clicking on the fork buton. In this example I am using this repo [App-Ideas Repository](https://github.com/DannieBabz/App-Ideas--JS)

![Fork Button](/images/img3.png)

2. You will be navigated to the create a new fork section in which you can change the name of the repository name. When you done, Click on the `Create fork` button.

![Fork Section](/images/img4.png)

3. Clone the repository using the instruction above on clone instruction.

4. In your terminal, create a new branch and switch to the branch using ` git checkout -b new-branch`

5. Open the clone repository with your favourite code editor e.g visual studio code(VSCode)


6. Edit the file, you want to edit, in my case its the README.md file. With VS Code, you get notification of the changes in the source control icon. 
7. Once you have modified the file, stage it using `git add .`, which will stage all the update you have made so far.
If you didn't see any message it means success.

8. You can use `git status` command to check the current stage and changes made. 

9. Still in the terminal, enter `git commit -m "update readme file with link to project readme`
![Git Commit Message](/images/img5.png)
10.  Push your branch to GitHub using  `git push --set-upstream origin new-branch`
11.  Navigate to the repository on github, and clicked on Pull requests on the menu. 
![Pull requests tab](/images/img6.png)
12. Click on `New pull request` green button. Change branch to your new created branch. Change the your repo branch to the new branch you just created.
![Comparing ](/images/img7.png)
13. Click on `Create pull request` button. Then click on Create pull request button at the button. 
![Comparing ](/images/img8.png)
14. Congratulation you just create your first pull request. 
![Comparing ](/images/img9.png)

## Commit 

Commit is used to capture a snapshot of repository currently staged changes. 

To commit a file, use the command `git commit -m "commit message"`.

`commit message` is the short descriptive message of what you did. 
![Git Commit Message](/images/img5.png)

## GitHub Desktop vs. Github CLI

If you are new to Github and you love Grahics User Interface(GUI) Github Desktop is the best option cause you have all tool to manage all github without seeing the command line.

Github CLI brings GitHub commands like making PR, actions and raising issues e.t.c to the terminal without interfacing with the GitHub Website.

In what ever world you choose, GitHub Desktop or Github CLI, don't forget to share with the world.
