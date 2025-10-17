# Deploying the portfolio to Netlify and Vercel

This repo is a static portfolio (HTML/CSS/JS). Use the steps below to deploy on Netlify and Vercel.

## Prerequisites
- Your repository is pushed to GitHub and public.
- You have Netlify and Vercel accounts (or create them).

## Netlify - Quick steps
### Option A: Drag & Drop (Fast)
1. Go to https://app.netlify.com/drop
2. Drag the entire `portfolio` folder from your computer onto the page
3. Netlify will upload and publish your site instantly

### Option B: Git Integration (Recommended)
1. Go to https://app.netlify.com/
2. Click "Add new site" → "Import from Git"
3. Connect your GitHub account and authorize Netlify
4. Select the repository: `-Hackathon-deploython-jeevan-reddy-17-10-2025`
5. Build command: (leave blank)
6. Publish directory: `.`
7. Click Deploy site
8. After deployment, you can change the site name and set a custom domain in Site settings

## Vercel - Quick steps
1. Go to https://vercel.com/
2. Click "New Project" → Import Git Repository
3. Connect your GitHub account and pick the repository `-Hackathon-deploython-jeevan-reddy-17-10-2025`
4. Framework Preset: **Other** (or leave default)
5. Build Command: (leave blank)
6. Output Directory: (leave blank)
7. Click Deploy

Vercel will detect the `vercel.json` and deploy the site as a static project.

## Notes & Tips
- Both Netlify and Vercel support custom domains once deployed.
- If using Git integration, every push to `main` will trigger an automatic redeploy.
- If you rely on environment variables in future (APIs, keys), set them in the Netlify/Vercel project settings (do NOT commit secrets into the repo).

## Repository
- GitHub repo: https://github.com/jeevan099293/-Hackathon-deploython-jeevan-reddy-17-10-2025

