# Git-Training
## Basic Commands
1. For first time user:
   - Setup Private Access Token on GitHub for remote access to Repositories.
   - Setup the email id and username on Git.
2. Initializaiton
   - To set the current directory to be managed/ tracked by Git.
   - git init
   - You can exclude files you wish not to be tracked by creating a .gitignore file and adding all the filenames or folder to be ignored by Git.
3. Clone the repo from Github
   - Make a new repo from Github, if not already exists
   - Copy the HTTPS path for cloning the remote repo on your local machine.
   - git clone <link>
4. Do your work
   - Create, edit your files.
5. Add files to staging area
i. git add <filename>
ii. To add all files in current directory use: git add .
6. Commit files
i. git commit
ii. Add a note
iii. Close the automatically opened editor
iv. Or git commit -m “your message”
v. You may even skip the staging part by adding –a flag.
7. Before pushing local changes to remote repo
i. First pull from the repo, to make sure there are no conflits
ii. git pull
iii. Now you may push
iv. git push
8. You may want to view the git history
   - git log
9. Extras
i. For creating a new branch
1. git branch <branch name>
ii. To view all branches
1. git branch
iii. To change current working branch
1. git checkout <branch name>
iv. To delete a branch
1. git branch –d <branch name>
v. To merge a branch with master
1. git merge <branch name>
vi. To rebase current branch onto master
1. git rebase master
vii. Revert
1. Creates a new commit with the previous commit removed (adds to
the chain)
2. git revert Head
viii. Reset
1. Resets to an old commit (shortens the chain)
2. git reset <commit hash, can be found from log>
