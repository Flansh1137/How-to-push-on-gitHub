# Push to GitHub (Windows)

Use **Command Prompt** or **PowerShell**.

## Steps
git init                       # Start git in this folder
git add .                      # Stage all files
git commit -m "First commit"   # Save changes
git branch -M main             # Set main branch
git remote add origin <repo-url>  # Connect to GitHub
git push -u origin main        # Upload code to GitHub

**New Branch (Optional)**
git checkout -b my-branch      # Create new branch
git add .
git commit -m "New branch"
git push -u origin my-branch   # Push branch to GitHub

**Note**
Same commands for CMD and PowerShell

![image](https://github.com/user-attachments/assets/6ce48c85-19ee-4e97-988f-861698fcca76)
