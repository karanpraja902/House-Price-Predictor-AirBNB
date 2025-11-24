# 🚀 GitHub Upload Guide

This guide will help you upload the Airbnb ML System project to GitHub.

## 📋 Prerequisites

- [ ] Git installed ([Download here](https://git-scm.com/downloads))
- [ ] GitHub account ([Sign up here](https://github.com/join))
- [ ] All project files ready

## 🎯 Quick Upload (3 Steps)

### Option 1: Using PowerShell Script (Windows - Recommended)

```powershell
# Run the setup script
.\setup_github.ps1
```

The script will:
1. ✅ Check Git installation
2. ✅ Initialize repository
3. ✅ Configure Git with your details
4. ✅ Create initial commit
5. ✅ Show next steps

### Option 2: Manual Setup

#### Step 1: Initialize Git Repository

```bash
# Navigate to project directory
cd c:\Users\rattu\Downloads\L-20

# Initialize Git
git init

# Configure Git
git config user.name "YourGitHubUsername"
git config user.email "your.email@example.com"
```

#### Step 2: Create Initial Commit

```bash
# Add all files
git add .

# Create commit
git commit -m "Initial commit: Karan Prajapat"
```

#### Step 3: Push to GitHub

**First, create a new repository on GitHub:**
1. Go to https://github.com/new
2. Repository name: `airbnb-ml-system` (or your preferred name)
3. Description: "End-to-End ML System Design for Airbnb Home Value Prediction"
4. Choose Public or Private
5. **DO NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

**Then, push your code:**

```bash
# Set main branch
git branch -M main

# Add remote repository (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/airbnb-ml-system.git

# Push to GitHub
git push -u origin main
```

### Option 3: Using GitHub CLI (if installed)

```bash
# Create repository and push in one command
gh repo create airbnb-ml-system --public --source=. --remote=origin
git push -u origin main
```

## 📁 What Gets Uploaded

### ✅ Included Files
- `README.md` - Main documentation
- `index.html` - Interactive documentation website
- `use_case_demo.html` - Prediction demo
- `styles.css` - Styling
- `script.js` - JavaScript functionality
- `use_case_demo.js` - Demo logic
- `airbnb_ml_system.py` - Full Python implementation
- `airbnb_ml_demo_simple.py` - Simplified version
- `requirements.txt` - Python dependencies
- `Makefile` - Project commands
- `LICENSE` - MIT License
- `.gitignore` - Git exclusions
- `CONTRIBUTING.md` - Contribution guidelines
- `CHANGELOG.md` - Version history
- `PROJECT_SUMMARY.md` - Quick overview
- `AirBnB_ML_System_Design.pdf` - Reference document

### ❌ Excluded Files (via .gitignore)
- `__pycache__/` - Python cache
- `*.pyc` - Compiled Python
- `.vscode/` - IDE settings
- Virtual environments
- Temporary files

## 🎨 Recommended Repository Settings

After uploading, configure your repository:

### 1. Add Topics
Go to repository → About → Settings (gear icon) → Add topics:
- `machine-learning`
- `ml-system-design`
- `airbnb`
- `xgboost`
- `shap`
- `data-science`
- `python`
- `interactive-demo`

### 2. Enable GitHub Pages (Optional)
To host the interactive demo:
1. Go to Settings → Pages
2. Source: Deploy from branch
3. Branch: `main` → `/` (root)
4. Save

Your demo will be available at:
`https://YOUR_USERNAME.github.io/airbnb-ml-system/`

### 3. Add Description
```
🏠 End-to-End ML System Design for Airbnb Home Value Prediction with interactive demos, SHAP explainability, and production-ready architecture
```

### 4. Add Website (if using GitHub Pages)
```
https://YOUR_USERNAME.github.io/airbnb-ml-system/
```

## 📊 Repository Structure Preview

```
airbnb-ml-system/
├── 📄 README.md                    # Main documentation
├── 🌐 index.html                   # Documentation website
├── 🎮 use_case_demo.html           # Interactive demo
├── 🎨 styles.css                   # Styling
├── ⚡ script.js                    # JavaScript
├── 🎯 use_case_demo.js             # Demo logic
├── 🐍 airbnb_ml_system.py          # Full implementation
├── 🐍 airbnb_ml_demo_simple.py     # Simplified version
├── 📦 requirements.txt             # Dependencies
├── 🛠️ Makefile                     # Commands
├── ⚖️ LICENSE                      # MIT License
├── 🚫 .gitignore                   # Git exclusions
├── 🤝 CONTRIBUTING.md              # Guidelines
├── 📝 CHANGELOG.md                 # Version history
├── 📋 PROJECT_SUMMARY.md           # Overview
└── 📚 AirBnB_ML_System_Design.pdf  # Reference
```

## 🔧 Troubleshooting

### Issue: "Git not recognized"
**Solution**: Install Git from https://git-scm.com/downloads

### Issue: "Permission denied (publickey)"
**Solution**: Set up SSH keys or use HTTPS with personal access token
- Guide: https://docs.github.com/en/authentication

### Issue: "Repository already exists"
**Solution**: Use a different repository name or delete the existing one

### Issue: "Large file warning"
**Solution**: The PDF might be large. If needed, add to .gitignore or use Git LFS

## ✅ Verification Checklist

After uploading, verify:
- [ ] All files are visible on GitHub
- [ ] README displays correctly
- [ ] Links in README work
- [ ] GitHub Pages is active (if enabled)
- [ ] Repository description is set
- [ ] Topics are added
- [ ] License is visible

## 🎉 Post-Upload

### Share Your Project
1. Add to your GitHub profile README
2. Share on LinkedIn/Twitter
3. Submit to awesome lists
4. Add to your portfolio

### Maintain Your Repository
```bash
# Make changes locally
git add .
git commit -m "Description of changes"
git push

# Pull latest changes
git pull
```

## 📞 Need Help?

- GitHub Docs: https://docs.github.com
- Git Docs: https://git-scm.com/doc
- Open an issue in the repository

---

**Ready to upload?** Run `.\setup_github.ps1` and follow the prompts! 🚀
