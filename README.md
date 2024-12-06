# This is git beginner  - get started repo.

## Tasks
- [x] Download git and configure the git locally.
- [x] Initialize the Repository.
- [x] First Commit.


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
