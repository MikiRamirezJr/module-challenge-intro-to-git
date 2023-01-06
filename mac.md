## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is arguably the most popular version control system in the world. A version control system records the changes made to our code overtime in a database called repository. With Git we can look at the history of the code, who is working on the code, and revert it back to its earlier state. To sum it up, 

2. What is the difference between Git and GitHub?
Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage repositories. Git is a software installed locally, GitHub is a service that is hosted on the web.


3. Why do we create a branch? 
We create a branch when we want to work on a code on our own without affecting the master branch.


4. What is the purpose of a Pull Request? 
Pull requests let others know about changes you've pushed to a branch in a repository on GitHub. A pull request is essentially asking that someone reviews and approves your changes before they become final.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout -b 'Branch-Name-Here'

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
'git fetch' fetches updates but does not merge them. Git merge merges a branch with the master branch. 'git pull' does a git fetch and then a merge.

7. What is a merge conflict?
A merge conflict happens when you merge branches that have competing commits, meaning more than one branch tried to change the same code.

8. How do you resolve a merge conflict?
The easiest way to resolve a conflicted file is to open it and make any necessary changes.
After editing the file, we can use the git add a command to stage the new merged content.
The final step is to create a new commit with the help of the git commit command,
git will then create a new merge commit to finalize the merge.
