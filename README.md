# Git-Training
Basic Commands
a. For first time user:
i. Setup Private Access Token on GitHub for remote access to Repositories.
ii. Setup the email id and username on Git.
b. Initializaiton
i. To set the current directory to be managed/ tracked by Git.
ii. git init
iii. You can exclude files you wish not to be tracked by creating a .gitignore file
and adding all the filenames or folder to be ignored by Git.
c. Clone the repo from Github
i. Make a new repo from Github, if not already exists
ii. Copy the HTTPS path for cloning the remote repo on your local machine.
iii. git clone <link>
d. Do your work
i. Create, edit your files.
e. Add files to staging area
i. git add <filename>
ii. To add all files in current directory use: git add .
f. Commit files
i. git commit
ii. Add a note
iii. Close the automatically opened editor
iv. Or git commit -m “your message”
v. You may even skip the staging part by adding –a flag.
g. Before pushing local changes to remote repo
i. First pull from the repo, to make sure there are no conflits
ii. git pull
iii. Now you may push
iv. git push
h. You may want to view the git history
i. git log
i. Extras
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
