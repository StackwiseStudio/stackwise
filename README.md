# Stackwise — SEO Content Website

## What's in This Folder

```
stackwise-website/
  index.html                                    ← Homepage (article hub)
  articles.css                                  ← Shared styles for all articles
  best-ai-tool-for-cold-email-writing.html
  best-ai-tool-for-customer-support.html
  best-ai-tool-for-product-descriptions.html
  best-ai-tool-for-summarising-research.html
  best-ai-tool-for-social-media-content.html
  best-ai-tool-for-spreadsheet-analysis.html
  best-ai-tool-for-seo-blog-posts.html
  best-ai-tool-for-transcribing-meetings.html
  best-ai-tool-for-invoice-automation.html
  best-ai-tool-for-sales-research.html
  best-ai-tool-for-training-materials.html
  best-ai-tool-for-proofreading.html
  README.md                                     ← This file
```

---

## How to Put This Live on the Internet (GitHub Pages)

### Step 1 — Create a GitHub Account
Go to **github.com** and sign up for free.

### Step 2 — Create a New Repository
- Click the **+** icon (top right) → **New repository**
- Name it: `stackwise`
- Set it to **Public**
- Click **Create repository**

### Step 3 — Upload All Files
- On the repository page, click **"uploading an existing file"**
- Select ALL files from this folder (Ctrl+A / Cmd+A to select all)
- Drag them into the upload area
- Scroll down, click **"Commit changes"**

### Step 4 — Enable GitHub Pages
- Click **Settings** (top of your repository)
- Scroll down to **Pages** in the left sidebar
- Under **Source**, select **main** branch → **/root** → click **Save**
- Wait 2 minutes

### Step 5 — Your Site is Live
Your website is now live at:
**https://YOUR-GITHUB-USERNAME.github.io/stackwise/**

---

## How to Add More SEO Articles

1. Generate a new article using the Stackwise SEO Generator
2. Click **"Download HTML"** — the file downloads automatically
3. Go to your GitHub repository
4. Click **"Add file"** → **"Upload files"**
5. Drag the downloaded HTML file in
6. Click **"Commit changes"**
7. The new article is live within 60 seconds

The homepage (index.html) already has a card for every article. To add a new
card to the homepage for new articles you generate, open index.html in any
text editor, find the ARTICLES array in the JavaScript section, and add a new
object following the same format as the existing ones.

---

## Your Waitlist Link
All articles link to: **https://stackwise-waitlist.netlify.app/**
Every article has 3 "Join Waitlist" buttons — top, middle, and bottom.

---

## To Add a Custom Domain (e.g. stackwise.com)
1. Buy your domain at namecheap.com or porkbun.com (~₹800–1200/yr)
2. In GitHub Settings → Pages → Custom domain → type your domain
3. In your domain registrar, add a CNAME record pointing to:
   `YOUR-USERNAME.github.io`
4. Your site is live at your custom domain within 24 hours

---

Built by Stackwise · March 2026
