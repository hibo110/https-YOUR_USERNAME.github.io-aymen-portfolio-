# 🚀 Quick Start Guide - Host Your Landing Page on GitHub

## ✅ Step 1: Local Setup (COMPLETED)
- ✅ Git repository initialized
- ✅ All files committed
- ✅ Branch renamed to `main`

## 📝 Step 2: Create GitHub Repository

1. **Go to GitHub and create a new repository:**
   - Visit: https://github.com/new
   - Repository name: `aymen-portfolio` (or any name you prefer)
   - Description: "Portfolio website for Aymen Mahfoudhi"
   - Make it **Public** (required for free GitHub Pages)
   - ❌ **DO NOT** check "Add a README file" (we already have one)
   - ❌ **DO NOT** add .gitignore or license
   - Click **"Create repository"**

2. **Copy the repository URL** (you'll need it in the next step)
   - It will look like: `https://github.com/YOUR_USERNAME/aymen-portfolio.git`

## 🔗 Step 3: Connect and Push to GitHub

After creating the repository, GitHub will show you commands. Use these instead:

```bash
git remote add origin https://github.com/YOUR_USERNAME/aymen-portfolio.git
git push -u origin main
```

**Replace `YOUR_USERNAME` with your actual GitHub username!**

## ⚙️ Step 4: Enable GitHub Pages

1. **Go to your repository on GitHub**
2. Click **Settings** (top menu bar)
3. Click **Pages** (left sidebar)
4. Under **"Source"**, select: **GitHub Actions**
5. The deployment will start automatically!

## 🌐 Step 5: Access Your Live Site

- Wait 1-2 minutes for the first deployment
- Go to the **Actions** tab to see deployment progress
- Your site will be live at: `https://YOUR_USERNAME.github.io/aymen-portfolio/`

## 📌 Quick Commands Reference

```bash
# Check status
git status

# Add changes
git add .

# Commit changes
git commit -m "Your commit message"

# Push to GitHub
git push

# View remote repository
git remote -v
```

## 🆘 Need Help?

- Check `DEPLOYMENT_GUIDE.md` for detailed instructions
- Check `README.md` for full documentation
- GitHub Pages docs: https://docs.github.com/en/pages

