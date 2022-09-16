## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is a tracked backup system that allows allows simultaneous ongoing work and corrections. It can be reverted back to a verified older working version or just referenced if needed. Ongoing work can be isolated and merged back into the main project line once vetted and ready to be decimated to the rest of the team without major down time or interruptions.
2. What is the difference between Git and GitHub? 
Git is the computer system commands and controls and Github is the cloud storage location and controls.
3. Why do we create a branch? 
To keep the main line protected from changes that have not been reviewed, that could cause errors/ bugs or override current functionality. It also allows multiple people to work at the same time without running over each other.
4. What is the purpose of a Pull Request? 
To notify others that a specific feature or item is ready for review.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. 
To switch between branches in git you use the git checkout command. Type git checkout 'branch_name' to change to the branch you want to switch to.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 
Git fetch checks to see if there is anything on the current branch that is different on the remote repo that is different from what your local repo has.  
Git merge combines the current branch into another, this could be the main but it may just be another branch or your local repo in the case of a pull. 
Git pull downloads any content from the remote repo that is missing from your local repo so that yours is current.  A pull is a fetch plus a merge in a single command.
7. What is a merge conflict? 
A merge conflict is when changes to the same file happen simultaneously and are then attempted to be uploaded.  This could be when a file is edited by 2 people, or one edits it and another removes it etc
8. How do you resolve a merge conflict?  
To resolve the conflict the changes have to reconciled. So a decision needs to be made as to which change will be the accepted one.  If 2 people changed the file, then it needs to be opened and the 2 changes need to be addressed, consolidated and finalized.  If it was removed and edited then final decision of if the file is needed at all needs to be resolved then the merge can be completed.  Typically there will be notations in the file stating where the conflicts are with characters <<<< head ====== >>>> branch to assist with this process.
