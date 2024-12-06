# Pull code into VS Code
git clone https://github.com/your-username/miware.git
cd miware
code .

# Create and switch to a new branch
git checkout -b tibco

# Make changes, stage, and commit them
git add .
git commit -m "Your commit message"

# Push the branch to GitHub
git push origin tibco

# Merge changes into main
git checkout main
git pull origin main
git merge tibco
git push origin main
