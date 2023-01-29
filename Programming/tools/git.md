# Git Cheat Sheet

## Initializing a Repository

- `git init`: Initialize a new Git repository
- `git clone <repo>`: Clone an existing repository from a remote source

## Staging and Committing Changes

- `git add <file>`: Stage a file for committing
- `git add .`: Stage all changes in the current directory
- `git commit -m "<message>"`: Commit the staged changes with a message
- `git reset <file>`: Unstage a file
- `git checkout -- <file>`: Discard changes in a file

## Viewing Commit History

- `git log`: View the commit history
- `git show <commit>`: Show details of a specific commit
- `git diff`: View the changes between commits

## Branching and Merging

- `git branch`: List all branches
- `git branch <branch-name>`: Create a new branch
- `git checkout <branch-name>`: Switch to a different branch
- `git merge <branch-name>`: Merge the specified branch into the current branch

## Remote Repositories

- `git remote`: List all remote repositories
- `git remote add <remote-name> <repo>`: Add a new remote repository
- `git push <remote-name> <branch-name>`: Push changes to a remote repository
- `git pull <remote-name> <branch-name>`: Pull changes from a remote repository

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
