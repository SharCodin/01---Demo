# Demo

Getting started with Git and Github.

## The setup

1. Create a new repository in Github.
2. Open terminal and navigate to a folder.
3. **git clone** *repository path, usually an HTML link*
4. This will create a copy of the repository in the folder. Similar to clone/download and then saving to that directory. 
5. **git status** *shows the changes done.*
6. **git add** *this will add new files*
7. **git commit** *this will commit changes done*
8. **git push** *this will upload to github and publish your local commits*

## Additional commands

1. **git init** *This will create an empty Git repository and initialize*
2. **git help** *this will display the help in powershell / cmd*

## Working with branch

If multiple people are working on the same projects or there are a lot of commits, it is good to work with branches. Having a branch means that the changes made to a branch will not reflect onto the master. This means, the code can be tested without affecting master. Once confirmed that everything is good, the branch and master can be merged. 

1. **git branch** *list the branches available*
2. **git branch <name>** *creates a new branch called <name>*
3. **git checkout <branch_name>** *switch to <branch_name>*
4. Once changes are done, **git commit** and **git push** to publish the branch to Github.
5. Navigate to Github and create a **pull request**
6. Under the pull requests, people can continue to review, ask questions and work on the branch.
7. Once completed, the branch and master can be merged.

## Initializing a repository if not cloned.

1. Create a folder to hold all the files. 
2. **git init** *initialize the repository / directory*
3. Commit the changes. 
4. When pushing the changes to Github, an error message saying ***"fatal: The current branch master has no upstream branch."***
5. Create an empty repository in Github.
6. git push --set-upstream <Github_link>
7. Committed changes are now live.