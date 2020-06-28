Task 1
1. What are git and GitHub?
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.                                                                                                                                                                                                                         Git is created by LINUS  TORVALDS. It is an open-source, free, and distributed version control system. Git has trunk-based development in it which involves branches in the repository in which we can create a new branch even while working with the current branch and also we can merge the new branch with the master branch if required at any point.
GitHub is a website in which we can upload projects that have version control over them. GitHub is a file or code-sharing service to collaborate with different people. 

2. Why GitHub is so popular and used in most of the projects?
GitHub is popular as:
• Largest shared repository
• Separate public and private repositories
• Shared Repositories which can be accessed by millions of users and make contributions to existing files or codes
• Easy Version Control
• Can be accessed anytime and anywhere

3. What are the other platforms similar to GitHub?
a. GitLab
b. BitBucket
c. Source Forge
d. AWS Code Commit

Task 2
1. How git workflow works?
There is one central repository. Each developer clones the repo, works locally on the code, makes a commit with changes, and push it to the central repository for other developers to pull and use in their work.

2.What are the different stages of git project? 
• Modified:
The code is saved in a repository which is public to all. Now anyone can make changes in it after cloning it from repository. This is called modification.
• Staged: 
The file is added from the working directory to the stagging directory by using command i.e git add. Now the file is ready to commit but is not committed yet.
• Commit: 
When we used the Git commit command, all the files that were staged in the Index are released here and the changes are committed to the local repository. Each commit command represents the changes made to project in the past, with the details about the time at which commit was made and the author of the code. So, finally when you make a commit, and it gets committed, then this simply means that you have successfully applied a certain modification to the code.

3.Is it possible to do a git commit before git add?If No,explain why?
No, it is not possible to use git commit before git add because git add adds the files from the working directory to the staging area and then the changes are saved using commit command in the local repository.

4. Why is git diff used?
It  is used to track the changes made on a file in a local directory or a working directory from the staging state.

5. Can we leave the commit messages as blank?
 Yes,this can be done using the following command :
 git commit -a --allow-empty-message -m "" 

Task 3
Q1. What is meant by the term fork and clone?
Ans. Forking of repository - we make a copy of the original repository and the repository remains on our GitHub account.                            Clonning-And when we clone a repository, the repository is copied to our local machine with the help of Git. 

Q2. What are branches in Github?
Ans. Using branches we can seperate our work from the main file. There is a default branch called master branch. To avoid mess up in the master branch we create local branches.

Q3. What is PR?

Ans. PR stands for Pull Request. This request is used to ask the person to merge our changes in his repo .We use this command after forking and clonning somone else project. 

Q4. Can we delete the master branch if not Why?

Ans. We cannot delete master branch because when we use command " git init", the Master branch gets activated by default. 
        A remote branch is slightly more involved than deleting a local one since we working with a repository that is likely not even on          our machine.

Q5. How can we delete a branch? 

Ans. To delete the local branch use one of the following:

        git branch -d branch_name