# 🚀 Step-by-Step Guide: Deploy Portfolio to GitHub

## Prerequisites
- [ ] Git installed on your computer
- [ ] GitHub account created

---

## Step 1: Install Git (if not already installed)

1. Download Git from: https://git-scm.com/download/win
2. Install with default settings
3. Verify installation by opening Command Prompt and typing:
   ```cmd
   git --version
   ```

---

## Step 2: Configure Git (First Time Only)

Open Command Prompt and run these commands with YOUR information:

```cmd
git config --global user.name "Jeevan Reddy"
git config --global user.email "jeevanreddy862@gmail.com"
```

---

## Step 3: Create GitHub Account

1. Go to: https://github.com/signup
2. Sign up with your email
3. Verify your email
4. Complete the setup

---

## Step 4: Initialize Git in Your Portfolio Folder

Open Command Prompt and run:

```cmd
cd "c:\Users\jeeva\OneDrive\Desktop\portfolio"
git init
```

You should see: "Initialized empty Git repository"

---

## Step 5: Add All Files to Git

```cmd
git add .
```

This stages all your files for commit.

---

## Step 6: Create First Commit

```cmd
git commit -m "Initial commit: Jeevan Reddy Portfolio Website"
```

---

## Step 7: Create GitHub Repository

1. Go to: https://github.com/new
2. Fill in the details:
   - **Repository name:** `portfolio` or `jeevan-portfolio`
   - **Description:** "Personal Portfolio Website - Full Stack Developer"
   - **Visibility:** ✅ **PUBLIC** (important for GitHub Pages)
   - **DO NOT** check "Initialize this repository with a README"
3. Click **"Create repository"**

---

## Step 8: Connect Local Repository to GitHub

After creating the repository, GitHub will show you commands. Run these (replace YOUR-USERNAME):

```cmd
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

**Note:** You may be asked to login to GitHub. Follow the prompts.

---

## Step 9: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down and click **Pages** (left sidebar)
4. Under "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** / (root)
5. Click **Save**
6. Wait 2-5 minutes

Your site will be live at:
```
https://YOUR-USERNAME.github.io/portfolio/
```

---

## 🎉 Your Portfolio is Now Live!

### Your URLs:
- **GitHub Repository:** `https://github.com/YOUR-USERNAME/portfolio`
- **Live Website:** `https://YOUR-USERNAME.github.io/portfolio/`

---

## 📝 Future Updates

When you make changes to your portfolio:

1. Save your changes
2. Open Command Prompt in portfolio folder
3. Run:
```cmd
git add .
git commit -m "Updated portfolio content"
git push origin main
```

Your website will automatically update in 2-3 minutes!

---

## 🆘 Common Issues & Solutions

### Issue: "git is not recognized"
**Solution:** Install Git from https://git-scm.com/download/win

### Issue: Authentication failed
**Solution:** 
- Use GitHub Desktop (easier): https://desktop.github.com/
- Or setup Personal Access Token

### Issue: Permission denied
**Solution:** Make sure you're logged into GitHub

### Issue: Repository not found
**Solution:** Double-check the repository URL

### Issue: Website shows 404
**Solution:** 
1. Wait 5-10 minutes for first deployment
2. Make sure repository is PUBLIC
3. Check GitHub Pages settings

---

## 💡 Alternative: Use GitHub Desktop (Easier!)

If command line is confusing, use GitHub Desktop:

1. Download: https://desktop.github.com/
2. Install and login to GitHub
3. Click **"Add"** → **"Add Existing Repository"**
4. Select your portfolio folder
5. Click **"Publish repository"**
6. Make it **PUBLIC**
7. Done! Now go to GitHub.com to enable Pages

---

## 🎯 Next Steps After GitHub

Deploy on two more platforms:

1. **Netlify:** https://www.netlify.com/
   - Sign in with GitHub
   - Import repository
   - Auto-deploy!

2. **Vercel:** https://vercel.com/
   - Sign in with GitHub
   - Import repository
   - Auto-deploy!

---

**Need help? Let me know which step you're stuck on!** 🚀
