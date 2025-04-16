Git Demo

# Commands

```
git init
git status
git add <file>
git commit -m "message"
git log
git remote add origin <url>
```

Common Commands
```
git add -A      # Add all files
```

## First Time Setup Process

1. Create a new repository on GitHub.

    -``` git init ```
2. Create an add an ignore file
    -``` touch .gitignore ```
    -``` git add .gitignore ```
3. Commit the changes
    -``` git commit -m "Initial commit" ```
4. Add the remote repository
    -``` git remote add origin <url> ```
5. Push the changes to the remote repository
    -``` git push origin <branch_name>```

Continuing to use Git Notes
    -``` git add -A ```
    -``` git commit -m "msg" ```
    -``` git push origin <branch_name> ```