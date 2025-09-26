# Manual GitHub Repository Setup Instructions

## Option 1: Using GitHub Web Interface (Recommended)

### Step 1: Create Repository on GitHub
1. Go to [github.com](https://github.com)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Fill in details:
   - **Repository name**: `insurance-predictor`
   - **Description**: `Interactive Insurance Cost Predictor using Machine Learning - Built with Streamlit and Random Forest`
   - **Visibility**: Public ✅
   - **Initialize**: Leave unchecked (we already have files)
5. Click "Create repository"

### Step 2: Push Your Local Code
After creating the repository, GitHub will show you commands. Use these:

```bash
git remote add origin https://github.com/YOUR_USERNAME/insurance-predictor.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Option 2: Using GitHub CLI (Alternative)

If you want to retry with GitHub CLI:

```bash
# Try creating repo directly
gh repo create insurance-predictor --public --description "Interactive Insurance Cost Predictor using ML"

# Set remote and push
git remote add origin https://github.com/YOUR_USERNAME/insurance-predictor.git
git push -u origin main
```

## What You'll Have After Setup:

Your GitHub repository will contain:
- ✅ `insurance_demo_app.py` - Main Streamlit application  
- ✅ `requirements.txt` - Python dependencies
- ✅ `README.md` - Professional documentation
- ✅ `linkedin_showcase_guide.md` - Marketing guide
- ✅ `linkedin_post_templates.md` - Post templates

## Next Steps After GitHub Setup:

1. **Copy your repository URL** (it will be: `https://github.com/YOUR_USERNAME/insurance-predictor`)
2. **Test the app locally** (we'll do this next)
3. **Deploy to Streamlit Cloud** using your GitHub repo
4. **Create your LinkedIn post** with live links

## Quick Commands to Run After Manual Setup:

```bash
# Add remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/insurance-predictor.git

# Push to GitHub
git push -u origin main

# Verify it worked
git remote -v
```

Ready for the next step once you've created the GitHub repository!