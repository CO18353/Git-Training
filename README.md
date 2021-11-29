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
   - git add <filename>
   - To add all files in current directory use: git add .
6. Commit files
   - git commit
   - Add a note
   - Close the automatically opened editor
   - Or git commit -m “your message”
   - You may even skip the staging part by adding –a flag.
7. Before pushing local changes to remote repo
   - First pull from the repo, to make sure there are no conflits
   - git pull
   - Now you may push
   - git push
8. You may want to view the git history
   - git log
9. Extras
   1. For creating a new branch
      - git branch <branch name>
   2. To view all branches
      - git branch
   3. To change current working branch
      - git checkout <branch name>
   4. To delete a branch
      - git branch –d <branch name>
   5. To merge a branch with master
      - git merge <branch name>
   6. To rebase current branch onto master
      - git rebase master
   7. Revert
      - Creates a new commit with the previous commit removed (adds to the chain)
      - git revert Head
   8. Reset
      - Resets to an old commit (shortens the chain)
      - git reset <commit hash, can be found from log>
