To update your GitHub repository with the updated files, follow these steps:

1. **Navigate to Your Project Directory**:
   Open Git Bash and use the `cd` command to navigate to the directory where your project files are located. For example:
   ```bash
   cd path/to/your/project
   ```

2. **Check the Status of Your Repository**:
   Before making any changes, check the status of your repository to see which files have been modified:
   ```bash
   git status
   ```

3. **Stage the Updated Files**:
   Stage the files you want to commit. You can stage all modified files using:
   ```bash
   git add .
   ```
   Or stage specific files by specifying their names:
   ```bash
   git add filename1 filename2
   ```

4. **Commit the Changes**:
   Commit the staged changes with a meaningful commit message:
   ```bash
   git commit -m "Update files with latest changes"
   ```

5. **Push the Changes to GitHub**:
   Finally, push the committed changes to your GitHub repository:
   ```bash
   git push origin main
   ```
   If your branch name is something other than `main`, replace `main` with the correct branch name.

6. **Verify the Update**:
   Go to your GitHub repository online to verify that the files have been updated.

Let me know if you encounter any issues or need further clarification!

git add filename # command to add a file 
git rm filename # command to delete a file 
git restore filename # command to update a file