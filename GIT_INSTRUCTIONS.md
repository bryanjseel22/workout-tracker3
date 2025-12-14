# How to Push to GitHub

## Step 1: Install Git (if not already installed)
Download from: https://git-scm.com/download/win

## Step 2: Create a GitHub Repository
1. Go to https://github.com
2. Click the "+" icon in the top right
3. Select "New repository"
4. Name it (e.g., "workout-tracker")
5. **Don't** initialize with README (you already have one)
6. Click "Create repository"

## Step 3: Push Your Code

Open PowerShell in this folder and run:

```powershell
# Initialize git (if not already done)
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit - Workout Tracker PWA"

# Add your GitHub repository (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Alternative: Use GitHub Desktop (Easier!)

1. Download GitHub Desktop: https://desktop.github.com/
2. Install and sign in with your GitHub account
3. Click "File" → "Add Local Repository"
4. Select this folder: `C:\Users\bryan\Desktop\work out file`
5. Click "Publish repository" button
6. Choose a name and click "Publish"

## After Pushing to GitHub

1. Go to https://vercel.com
2. Sign up/Login (can use GitHub account)
3. Click "Add New Project"
4. Import your GitHub repository
5. Click "Deploy" (no configuration needed!)
6. Your app will be live in seconds!

