# Deployment Guide

This guide will help you deploy your portfolio website on three different hosting platforms.

## Prerequisites

- Git installed on your computer
- GitHub account
- Accounts on Netlify, Vercel (free)

## Step 1: Initialize Git Repository

```bash
cd c:\Users\jeeva\OneDrive\Desktop\portfolio
git init
git add .
git commit -m "Initial commit: Personal portfolio website"
```

## Step 2: Push to GitHub

1. Create a new repository on [GitHub](https://github.com/new)
   - Name it something like `portfolio` or `personal-website`
   - Keep it public
   - Don't initialize with README (we already have one)

2. Link and push your local repository:
```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git branch -M main
git push -u origin main
```

## Step 3: Deploy on GitHub Pages

### Option A: Using GitHub Settings
1. Go to your repository on GitHub
2. Click on **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait a few minutes, your site will be live at:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

### Option B: Using GitHub Actions (Advanced)
GitHub Pages will deploy automatically from the main branch.

## Step 4: Deploy on Netlify

### Option A: Drag and Drop (Easiest)
1. Go to [Netlify](https://www.netlify.com/)
2. Sign up/Login
3. Drag and drop your portfolio folder to the Netlify dashboard
4. Your site will be live instantly!

### Option B: Git Integration (Recommended)
1. Go to [Netlify](https://app.netlify.com/)
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **GitHub** and authorize Netlify
4. Select your portfolio repository
5. Configure build settings:
   - Build command: (leave empty)
   - Publish directory: (leave empty or `.`)
6. Click **Deploy site**
7. Your site will be live at: `random-name.netlify.app`
8. You can customize the domain in Site Settings

### Custom Domain on Netlify (Optional)
1. Go to Site Settings → Domain Management
2. Click "Add custom domain"
3. Follow the instructions to configure DNS

## Step 5: Deploy on Vercel

1. Go to [Vercel](https://vercel.com/)
2. Sign up/Login with GitHub
3. Click **"Add New Project"**
4. **Import** your GitHub repository
5. Configure project:
   - Framework Preset: **Other**
   - Build Command: (leave empty)
   - Output Directory: (leave empty)
6. Click **Deploy**
7. Your site will be live at: `your-project.vercel.app`

### Custom Domain on Vercel (Optional)
1. Go to Project Settings → Domains
2. Add your custom domain
3. Follow DNS configuration instructions

## Summary of Deployment URLs

After completing all steps, you'll have three live URLs:

1. **GitHub Pages**: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`
2. **Netlify**: `https://your-site-name.netlify.app`
3. **Vercel**: `https://your-project.vercel.app`

## Updating Your Portfolio

Whenever you make changes:

```bash
git add .
git commit -m "Description of changes"
git push origin main
```

All three platforms will automatically redeploy with your changes:
- **GitHub Pages**: 1-5 minutes
- **Netlify**: 1-2 minutes (automatic)
- **Vercel**: 30 seconds - 1 minute (automatic)

## Troubleshooting

### GitHub Pages not showing
- Check that the repository is public
- Ensure GitHub Pages is enabled in Settings
- Wait 5-10 minutes for first deployment

### Netlify build failed
- Ensure there are no errors in your HTML/CSS/JS
- Check the deploy logs for specific errors

### Vercel deployment issues
- Verify your repository is connected
- Check build logs in the Vercel dashboard

## Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Netlify Documentation](https://docs.netlify.com/)
- [Vercel Documentation](https://vercel.com/docs)

---

**Good luck with your deployment! 🚀**
