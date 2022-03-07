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

1. Git is a code version control system, it is open source and distributed.
2. Github is a company the provides cloud based git hosting service, it's kind of like a gui on top of git, for easy collaboration among developers.
3. We create a branch so that we can make code changes to our own files, and avoid manipulating the main branch. 
4. A pull request is a state in which our modified codefiles are awaiting review, before being considered for a merger to the main branch. 
5. You can use this command to switch branches: git checkout <branch name>
6. 'git fetch' will download files from remote repo to your local computer, 'git merge' will merge different code branches together with your branch, and 'git pull' will do both of these functions; fetching with intention to merge.
7. A merge conflict happens when there are commits which interfere with eachother, such as modifications to the same areas of code or insertions and deletions that cancel eachother.
8. You must review the conflicting areas between the branches being compared and resolve all of the issues specified. 