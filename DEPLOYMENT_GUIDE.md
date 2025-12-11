# GitHub Pages Deployment Guide

## Quick Setup (5 minutes)

### Option 1: New Repository (Recommended)

1. **Create a new repository on GitHub:**
   - Go to https://github.com/new
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

### Option 2: User/Organization Site

For a cleaner URL like `https://hibo110.github.io/`:

1. **Create a special repository:**
   - Repository name MUST be: `hibo110.github.io`
   - Make it Public
   - Create repository

2. **Upload index.html** (same as Option 1, step 2)

3. **GitHub Pages activates automatically**
   - Your site will be at: `https://hibo110.github.io/`

## Custom Domain (Optional)

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

## Updating Your Site

To update the landing page:
1. Go to your repository
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make your changes
5. Commit changes

Changes will be live in 1-2 minutes.

## Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for the deployment status
- Ensure repository is Public

**404 Error?**
- Verify the file is named exactly `index.html` (lowercase)
- Check that GitHub Pages is enabled in Settings

**Need help?**
- GitHub Pages Documentation: https://docs.github.com/en/pages
