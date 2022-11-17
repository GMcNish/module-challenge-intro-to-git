## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

Answers:
1.
Quoting geeksforgeeks.org, "Git is a distributed version control system for tracking changes in source code during software development." It is used to track changes in sets of files.
2.
once again, from geeksforgeeks.org "GitHub is a web-base Git repository hosting service".  Github is a web based location where git repositories can be stored, whereas Git is the control system for tracking changes. 
3.
We create a branch so that we can make changes that can be evaluated prior to being merged with main. 
4.
A pull request is used to review differences between brances 
5.
git checkout 'branch-name'
I also learned a cool trick, "git checkout -" will return you to the branch you were in last.
6.
git fetch: downloads commits from a remote repo to a local repository. but does not force you to merge the changes. 
git merge: merges branches together. 
git pull: pulls to the local environment commits made to a branch on a remote.

according to atlassian.com, git fetch is a safe way to review commits before integrating them. 

The git pull command will download the remote content and also excute git merge with the new content. 

Therefore git fetch downloads a remote repo.
The git merge command merges the branches.
The git pull command does both.
7.
From the GitHub Docs: "Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.
8.
Merge conflicts can either be resolved on GitHub using the conflict editor, in the case competing line changes.  For other types of conflict it must be resolved in a local clone where decisions aboout which version to keep can be decided line by line in a text editor such as Visual Studio Code. 
