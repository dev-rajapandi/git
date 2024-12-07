# This is git beginner  - get started repo.

## Tasks
- [x] Download git and configure the git locally.
- [x] Initialize the Repository.
- [x] First Commit.
- [x] Git logs.
- [x] Git Branches.


### Download git and configure the git locally.
1. Download git from the official site and install it.
2. Set the git username and email using the below comments.
   
   ```shell
   git -v # it will show the git version

   git config --global user.name <username> # To set username

   git config --global user.name # It will show the configured username
   
   git config --global user.email <email> # To set email

   git config --global user.email # It will show the configured email
   ```

### Initialize the Repository. 
1. Create the directory for your/ in existing local code (project) run the below script to initialize the git.
   ```shell
   git init # Initialize the git locally
   ```

### First Commit.
1. Create the file/Files.(README.md here)
2. Stage your file changes using the following comment.
   ```shell
   git add <filename> # Staging the single file change.

   git add . # Staging all the file changes.

   git status # It will show the staus of changed files.

   git reset <filename> # Unstage the single file.

   git rest # Unstage all the files.
   ```
3. Commit message
   ```shell
   git commit -m <short-commit-messge> # Commit changes with meaningful message
   ```
4. Reset last commit
   ```shell
   git reset --soft HEAD~1 # Uncommit the last one and keep changes in staging
   git reset --mixed HEAD~1 # Uncommit and unstage the last one
   git reset --hard HEAD~1 # Delete the last commit
   ```
### Git logs.
1. See the git history
   ```shell
   git log # it will show the git activities

   git log --oneline # it will show the git activities in onrline with short commit hash

   git log --oneline --author=RP # It will show the commits made by the specific user.

   git log --oneline --since="2024-12-01" # It will show the commits made after specific date time.

   git diff 81de41 dec13e # Shows the difference between two commits.
   ```

### Git Branches
1. Create a new branch.
   ```shell
   git branch new_branch
   ```
2. Switch to new branch.
   ```shell
   git checkout new_branch
   ```
3. Switch to master branch. (Both were same)
   ```shell
   git checkout master
         or
   git swith master
   ```
4. Create and switch to new branch in single comment.
   ```shell
   git checkout -b new_branch_2
            or
   git switch -c new_branch_3
   ```