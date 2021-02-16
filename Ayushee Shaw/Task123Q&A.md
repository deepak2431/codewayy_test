#Task 1:


##1. What are the GIT and GitHub? Why GitHub is so popular in most of the projects?
In today's world and industry, there are many softwares and codes developed by engineers. With such codes and vast project, there is a need of some repository as well as a version controller.Git is a version control system that is used to manage and keep track of one's source code (or software code) and it's history of changes viz different versions . Whereas GitHub is a cloud-based hosting service. Git is one of the distributed version control system commonly used for open source and commercial software development.


##2. What are the other platforms similar to GitHub?
a. Gitlab 
b. Bitbucket
c. SourceForge 
d. launchpad
e. Google Cloud source Repositories


#Task 2:


##Q1 how GIT workflow works?
Ans. 
Developers start by cloning the central repository. In their own local copies of the project, they edit files and commit changes as they would with SVN; however, these new commits are stored locally - they’re completely isolated from the central repository. This lets developers defer synchronizing upstream until they’re at a convenient break point.

To publish changes to the official project, developers "push" their local master branch to the central repository. This is the equivalent of svn commit, except that it adds all of the local commits that aren’t already in the central master branch.

##Q2 what are the different stages of a GIT the project as commit, add?
Ans. 

Git, goes through three stages — Modified, Staged, and Committed.
###*Modified:
Under Git we can create a repository, a repository is basically a kind of a directory that contains all the files related to our code. So, in the repository we can write code, and maintain it. Once, the code is written, anyone willing to make some modification can make those changes in their own remote repository. A remote repository is a local copy (one that you create on your local machine) of the original project that is being maintained via Git. So, basically we can make changes to our copy of the project without hampering the original code. This is called Modification, i.e. making some additions to the original project.
###*Staged:
We can make changes to the project without hampering the original version, but how do we apply those changes to our remote repository? So, we use the commands in the Git command line — git add. So, this command tracks the new changes and pushes it to the staging area. So, staging area is place prior to the actual implementation of changes, i.e. this area contains all the added files that contain new code, which are ready to be joined to the remote repository. So, all the new files are first pushed to the staging area.Staging area is a place where all the new files are finally ready to be joined to the remote repository.
###*Commit:
This is the final stage, as this stage finally applies the new changes to the remote repository. So a commit is a set of new files that are being added to a project as part of the modification. Each commit represents the changes made to project in the past, with the details about the time at which commit was made and the author of the code. So, finally when we make a commit, and it gets committed, then this simply means that we have successfully applied a certain modification to the code.

##3.Is it possible to do a git commit before git add?If No,explain why?
Ans.
No, it is not possible as git add command add changes in the working directory and then the changes are saved using commit command.

##4.Why is git diff used?
Ans.
Difference command is used to track the differences or changes made on a file in a working directory.

##5. Can we leave the commit messages as blank?
Ans.
Yes,we can do that by using the command:
git commit -a --allow-empty-message -m "" 


#Task 3:


##a. What is meant by the term fork and clone?
Ans-
fork of repository means  we create a copy of the original repository (upstream repository) but the repository remains on our GitHub account. Whereas, when we clone a repository, the repository is copied on to our local machine with the help of Git.

##b. What are branches in Github?
Ans-
We always create a branch from an existing branch. Typically, we might create a branch from the master branch of our repository. We can then work on this new branch in isolation from changes that other people are making to the repository. A branch we create to build a feature is commonly referred to as a feature branch or topic branch.

##c. What is PR?
Ans-
Pull Requests (sometimes called Merge Requests in other systems like GitLab) is really just a request that someone else review the work that you’ve done and merge your changes in. When you create a pull request, you need to select 2 branches on GitHub, the branch that you’ve made your changes on, and the branch where you would want to merge your changes into. Because Pull Requests occur in GitHub, you would need to push your branch to GitHub before you create the request.

##d. Can we delete the master branch if not Why?
Ans-Yes

##e. How can we delete a branch? 
Ans- To delete a  branch, you can’t use the git branch command. Instead, use the git push command with --delete flag, followed by the name of the branch you want to delete. You also need to specify the remote name (origin in this case) after git push.
