# Samrush - Free Bulk DA PA Checker

Official high-converting landing page for **Samrush** (Free Bulk DA PA Checker – Check 10 DA PA at a time).

## Live Domain
- **URL**: `https://samrush.com`

## Features
- **Authentic Semrush UI/UX**: Deep Navy (`#111322`), flame orange CTAs (`#ff642d`), Plus Jakarta Sans typography, and authentic SaaS component structure.
- **3-Step Google Search Verification**: Requires users to complete 3 quick Google topic searches to prevent bot spam and unlock the free bulk tool.
- **Bulk 10 DA PA Checker**: Real-time analysis of Domain Authority (DA 1–100), Page Authority (PA 1–100), Spam Score, and Backlinks for up to 10 domains simultaneously.
- **CSV Export**: 1-click client-ready spreadsheet download.
- **Full SEO & Schema.org**: WebApplication and FAQPage JSON-LD rich snippets.

## How to Deploy to GitHub Pages (Fastest Method)

### Step 1: Open Terminal in Project Folder
```bash
cd /Users/kapilsaini/.gemini/antigravity/scratch/samrush-dapa-checker
```

### Step 2: Initialize Git and Commit
```bash
git init
git add .
git commit -m "Launch Samrush Free Bulk DA PA Checker Landing Page"
```

### Step 3: Create GitHub Repository & Push
1. Go to [github.com/new](https://github.com/new) and create a repository (e.g. `samrush` or `samrush-dapa-checker`).
2. Run:
```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/samrush.git
git push -u origin main
```

### Step 4: Turn ON GitHub Pages
1. On GitHub, go to your repository **Settings** &rarr; **Pages** (left menu).
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: `/(root)`
3. Click **Save**.
4. In 60 seconds, your site is live!

### Step 5: Custom Domain Setup (samrush.com)
If you own `samrush.com`:
1. In **Settings** &rarr; **Pages**, enter `samrush.com` in **Custom domain**.
2. In your domain registrar (GoDaddy, Namecheap, Cloudflare), set DNS:
   - **A Records**:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME Record**:
     - Host: `www` &rarr; Points to: `YOUR_USERNAME.github.io`
