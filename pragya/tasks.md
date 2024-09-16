#TASK 1
#What is Git and GitHub?

Git:-Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.Git also tracks the history of changes to a project’s source code including what specifically has been changed and who has changed what parts and when have they been changed this feature is termed as Version Control.

GitHub is a web-based service for version control using Git. One can look at other people’s code, identify issues with their code and even propose changes. This also helps us in improving your code and also makes is
GitHub is a
A publishing tool
 
A version control system

A collaboration tool

It allows developers to host their files in a ‘Git Repository’ so that other people can collaborate on projects with them Its like a social networking site for developers.

#Why is GitHub so popular?
Automatically tracks every minute change in your project
Allows us to revert back to a previous version no matter how many times you changed your files.
It allows people to work together on the same project at the same time without disturbing each other’s files
Easy to learn and work on .


1. What is git and gitHub?
Git- Git was created by Linus Torvalds. Git is a type of version control system that makes it easier to track changes to files or in the source code.
It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. It is a program installed in a system.
GitHub- It provides hosting for software development version control using Git. It allows us to create remote repository on website and provides a platform to bring teams together.

2. Why GitHub is so popular and used in most of the projects?
1. It supports all programing languages.
2. Easily accessible
3. Provides secure cloud storage
4. Teams can work together easily

3. What are the other platforms similar to GitHub?
1. SourceForge
2. Launchpad
3. GitBucket
4. Gitlab

TASK 2

Initialize the central repository

￼

First, someone needs to create the central repository on a server. If it’s a new project, you can initialize an empty repository.

Hosted central repositories

Central repositories are often created through 3rd party Git hosting services like Bitbucket Cloud or Bitbucket Server

Clone the central repository

Next, each developer creates a local copy of the entire project. This is accomplished via the git clone command:

Make changes and commit

Once the repository is cloned locally, a developer can make changes using the standard Git commit process

Push new commits to central repository

Once the local repository has new changes committed. These change will need to be pushed to share with other developers on the project.
What are the different stages of a git project?
Working Area

The Git version control system does not handle files that are in the Working area only. That means the Git does not track them. That is why these files are sometimes called untracked files.
Generally, programmers do not includes, ./bin folder or / folder.

Staging Area

Git tracks The files that are in the staging area and analyse those files to check what has changed between the current commit and the last commit.

Repository

In this stage, the git version control system has all your commits and it knows what has been changed in the commit. It is the snapshot of what you changed in a commit.

I is it possible to do a GIT commit before a git add if you have made any changes explain why ?
No it is not possible to perform a GIT commit before they get ad add the commit command can only be applied on added data the first adding data and then commit it to the repository.
d.Why is git diff used?
This command is used to check the difference between the files in the stage and in the workspace.
  Can we leave the commit message as blank?
Yes we can do it by using the below command :
git commit -a --allow-empty-message -m ""

GitHub repository link

**TASK 3**

#Q1. What is meant by the term clone and fork?
Ans: A Clone is used to create a local copy and it it modifies files locally as well.
Making a personal copy from some others project is known as a fork, it also help us to modify and make changes without affecting the original content.

#Q2.What are branches in github?
Ans: A branch is an individual project pr files inside a repository. Once we have made changes in the file we can merge that branch to the master branch.All the branches are independent to each other.

#Q3.What is PR?
Ans: Pull Request: it is a command informing  about the changes that we have made in a project or in a branch .When this command is executed it means that we are requesting others to view the changes that we have made and merge it with the master branch.

#Q4.Can we delete the master branch if not why?
Ans: We can delete the master branch but for this we need to create a new branch as the default .
#Q.How can we delete a branch?
Ans: git branch -d command is uesd to delete the branch.

https://github.com/pragyadiwakar/gitseries
https://github.com/pragyadiwakar/gitseries/tree/master/pragyaa

