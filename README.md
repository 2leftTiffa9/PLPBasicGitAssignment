# PLPBasicGitAssignment

This repository is a basic introduction to the Git and GitHub workflow, emphasizing repository creation, local setup, making changes, committing, and pushing to GitHub.

## Steps Taken

### Task 1: Repository Setup

1. **GitHub Repository Creation:**
   - Logged in to GitHub.
   - Created a new repository named "PLPBasicGitAssignment".
   - Initialized it with a README file.

### Task 2: Local Setup

2. **Local Folder Setup:**
   - Created a new folder named "PLPBasicGitAssignment" on the local machine.
   - Opened a terminal or command prompt and navigated to the created folder.

3. **Git Initialization:**
   - Initialized a new Git repository in the local folder:
     ```bash
     git init
     ```

4. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository:
     ```bash
     git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git
     ```

### Task 3: Making Changes

5. **Create a File:**
   - Inside the local folder, created a new text file named `hello.txt`.
   - Added a simple text message "Hello, Git!" to the file.

6. **Committing Changes:**
   - Staged the changes:
     ```bash
     git add hello.txt
     ```
   - Committed the changes:
     ```bash
     git commit -m "Add hello.txt with my name Darren Kimonge"
     ```

### Task 4: Pushing to GitHub

7. **Pushing to GitHub:**
   - Pushed the committed changes to the GitHub repository:
     ```bash
     git push -u origin main
     ```

### Task 5: Verification

8. **Verify on GitHub:**
   - Visited the GitHub repository in a web browser to confirm that the `hello.txt` file and commit message are visible.

### Submission

- Ensured all changes are pushed to the GitHub repository.
- Shared the link to the GitHub repository with the instructor or submitted it as per class instructions.

## Summary of Commands Used

```bash
# Local setup
cd path/to/PLPBasicGitAssignment
git init

# Connecting to GitHub
git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git

# Making changes
echo "Hello, Git!" > hello.txt
git add hello.txt
git commit -m "Add hello.txt with a greeting"

# Pushing to GitHub
git push -u origin main
