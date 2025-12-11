# Aymen Mahfoudhi - Portfolio Website

Portfolio website for Aymen Mahfoudhi, International Business Developer specializing in commercial expansion between Europe, North Africa, and Gulf countries.

## 🚀 Quick Deployment

This site is designed to be deployed on GitHub Pages. Follow the deployment guide below or use the automated GitHub Actions workflow.

### Option 1: Automated Deployment (Recommended)

**Step-by-step setup:**

1. **Initialize Git repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit with automated deployment setup"
   ```

2. **Create a new repository on GitHub:**
   - Go to https://github.com/new
   - Repository name: `aymen-portfolio` (or any name you prefer)
   - Make it **Public** (required for free GitHub Pages)
   - ❌ Do NOT check "Add a README file" (we already have one)
   - Click "Create repository"

3. **Push your code to GitHub:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/aymen-portfolio.git
   git branch -M main
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` with your GitHub username.

4. **Enable GitHub Pages with GitHub Actions:**
   - Go to your repository on GitHub
   - Click **Settings** (top menu)
   - Click **Pages** (left sidebar)
   - Under "Source", select: **GitHub Actions**
   - The workflow will automatically trigger

5. **Verify deployment:**
   - Go to the **Actions** tab in your repository
   - You should see "Deploy to GitHub Pages" workflow running
   - Wait 1-2 minutes for the first deployment
   - Your site will be live at: `https://YOUR_USERNAME.github.io/aymen-portfolio/`

**✨ Benefits of automated deployment:**
- ✅ Automatic deployment on every push to `main` branch
- ✅ No manual configuration needed after initial setup
- ✅ Deployment history visible in Actions tab
- ✅ Easy rollback if needed
- ✅ Works with any branch structure

### Option 2: Manual GitHub Pages Setup

1. **Create a new repository on GitHub:**
   - Repository name: `aymen-portfolio` (or any name you prefer)
   - Make it **Public**
   - ✅ Check "Add a README file"
   - Click "Create repository"

2. **Upload your landing page:**
   - In your new repository, click "Add file" → "Upload files"
   - Drag and drop `index.html`
   - Commit message: "Add landing page"
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages (left sidebar)
   - Under "Source", select branch: `main`
   - Folder: `/ (root)`
   - Click "Save"

4. **Access your site:**
   - Wait 1-2 minutes for deployment
   - Your site will be live at: `https://hibo110.github.io/aymen-portfolio/`

### Option 3: User/Organization Site

For a cleaner URL like `https://hibo110.github.io/`:

1. **Create a special repository:**
   - Repository name MUST be: `hibo110.github.io`
   - Make it Public
   - Create repository

2. **Upload index.html** (same as Option 2, step 2)

3. **GitHub Pages activates automatically**
   - Your site will be at: `https://hibo110.github.io/`

## 🌐 Custom Domain (Optional)

If you have a custom domain (e.g., aymenmahfoudhi.com):

1. In repository Settings → Pages → Custom domain
2. Enter your domain name
3. Configure DNS with your domain provider:
   - Add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add a CNAME record pointing to: `hibo110.github.io`

## 📝 Updating Your Site

To update the landing page:
1. Edit `index.html` locally
2. Commit and push changes to GitHub
3. Changes will be live in 1-2 minutes (or automatically via GitHub Actions)

## 🛠️ Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for the deployment status
- Ensure repository is Public

**404 Error?**
- Verify the file is named exactly `index.html` (lowercase)
- Check that GitHub Pages is enabled in Settings

**Need help?**
- GitHub Pages Documentation: https://docs.github.com/en/pages
- See `DEPLOYMENT_GUIDE.md` for detailed instructions

## 📄 Files

- `index.html` - Main portfolio website
- `DEPLOYMENT_GUIDE.md` - Detailed deployment instructions
- `.github/workflows/deploy.yml` - Automated deployment workflow

## 📧 Contact

For questions about deployment or the website, please refer to the deployment guide or GitHub Pages documentation.

