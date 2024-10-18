# Common Git and GitHub Commands

Here are some commonly used Git and GitHub commands that you'll likely use on a daily basis:

## Basic Git Commands

1. **`git init`**
   - **Purpose**: Initializes a new Git repository in the current directory.
   - **Usage**: 
     ```bash
     git init
     ```

2. **`git clone <repository_url>`**
   - **Purpose**: Clones a remote repository to your local machine.
   - **Usage**:
     ```bash
     git clone https://github.com/username/repo.git
     ```

3. **`git status`**
   - **Purpose**: Displays the status of the working directory and staging area, including modified, staged, and untracked files.
   - **Usage**:
     ```bash
     git status
     ```

4. **`git add <file>`**
   - **Purpose**: Stages changes in a file for the next commit.
   - **Usage**:
     ```bash
     git add filename.txt
     ```
   - To add all changes:
     ```bash
     git add .
     ```

5. **`git commit -m "<message>"`**
   - **Purpose**: Commits the staged changes to the repository with a descriptive message.
   - **Usage**:
     ```bash
     git commit -m "Initial commit"
     ```

6. **`git push origin <branch>`**
   - **Purpose**: Pushes local commits to the specified remote branch.
   - **Usage**:
     ```bash
     git push origin main
     ```

7. **`git pull origin <branch>`**
   - **Purpose**: Fetches and merges changes from the specified remote branch into the current branch.
   - **Usage**:
     ```bash
     git pull origin main
     ```

8. **`git branch`**
   - **Purpose**: Lists all branches in the current repository, highlighting the active branch.
   - **Usage**:
     ```bash
     git branch
     ```

9. **`git checkout <branch>`**
   - **Purpose**: Switches to the specified branch.
   - **Usage**:
     ```bash
     git checkout feature-branch
     ```

10. **`git checkout -b <new-branch>`**
    - **Purpose**: Creates a new branch and switches to it.
    - **Usage**:
      ```bash
      git checkout -b new-feature
      ```

11. **`git merge <branch>`**
    - **Purpose**: Merges the specified branch into the current branch.
    - **Usage**:
      ```bash
      git merge feature-branch
      ```

12. **`git log`**
    - **Purpose**: Displays a history of commits for the current branch.
    - **Usage**:
      ```bash
      git log
      ```

13. **`git reset <file>`**
    - **Purpose**: Unstages a file from the staging area.
    - **Usage**:
      ```bash
      git reset filename.txt
      ```

14. **`git diff`**
    - **Purpose**: Shows changes between the working directory and the index (staged files).
    - **Usage**:
      ```bash
      git diff
      ```

## GitHub-Specific Commands

15. **`git remote -v`**
    - **Purpose**: Lists the remote repositories linked to your local repository.
    - **Usage**:
      ```bash
      git remote -v
      ```

16. **`git remote add <name> <url>`**
    - **Purpose**: Adds a new remote repository.
    - **Usage**:
      ```bash
      git remote add origin https://github.com/username/repo.git
      ```

17. **`git fetch`**
    - **Purpose**: Retrieves updates from a remote repository without merging them.
    - **Usage**:
      ```bash
      git fetch origin
      ```

18. **`git stash`**
    - **Purpose**: Temporarily saves changes that are not ready to be committed.
    - **Usage**:
      ```bash
      git stash
      ```

19. **`git stash pop`**
    - **Purpose**: Applies the latest stashed changes back to the working directory.
    - **Usage**:
      ```bash
      git stash pop
      ```

## Tips for Using Git and GitHub

- **Consistent Commit Messages**: Use clear and descriptive commit messages to make your project history easier to understand.
- **Branching Strategy**: Use branches for new features, bug fixes, or experiments to keep your main branch stable.
- **Pull Before Push**: Always pull the latest changes before pushing to avoid conflicts.

These commands should cover most of the day-to-day operations you'll encounter while using Git and GitHub. Let me know if you need more information on any specific command!
