# Initialize Git repository (if not already done)
git init

# Add all files to Git
git add .

# Create your first commit
git commit -m "Initial commit"

# Add the GitHub repository as remote (replace USER and REPO with your values)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push the code to GitHub
git push -u origin main
