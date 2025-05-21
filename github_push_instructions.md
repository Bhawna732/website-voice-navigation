# GitHub Push Instructions

## Prerequisites
1. Create a GitHub account if you don't have one: https://github.com/signup
2. Install Git if not already installed: https://git-scm.com/downloads

## Steps to Push to GitHub

### 1. Initialize Git Repository
Open a terminal or command prompt in your project folder (`d:\SHL Assignment`) and run:
```
git init
```

### 2. Add Your Files
Add all your files to the staging area:
```
git add .
```

### 3. Create Initial Commit
Commit your files with a message:
```
git commit -m "Initial commit of voice recognition and grammar engine projects"
```

### 4. Create a GitHub Repository
1. Go to GitHub.com and log in
2. Click the "+" icon in the upper right corner and select "New repository"
3. Enter a repository name (e.g., "SHL-Assignment" or "Voice-Recognition-Project")
4. Optionally add a description
5. Keep the repository public or make it private
6. Click "Create repository"

### 5. Link and Push to GitHub
GitHub will show commands to push an existing repository. Use these commands:
```
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and the name of the repository you created.

### 6. Verify
Visit your GitHub repository URL to confirm your code has been pushed successfully.

## Additional Information
- To update your repository after making changes:
  ```
  git add .
  git commit -m "Description of changes"
  git push
  ```
- For more information on using Git and GitHub, visit: https://docs.github.com/en/get-started
