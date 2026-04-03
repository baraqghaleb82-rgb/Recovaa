# Recova Website

Privacy-Preserving AI Recommendations — Innovate UK CyberASAP Project 10193687

## Structure

```
recova/
├── index.html          # Homepage
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Interactions & animations
└── pages/
    ├── about.html      # About page
    └── contact.html    # Contact / Early Access page
```

## Deploying to GitHub Pages (Step by Step)

### 1. Create a GitHub account
Go to https://github.com and sign up if you don't have an account.

### 2. Create a new repository
- Click the **+** icon → **New repository**
- Name it: `recova-website` (or just `recova`)
- Set to **Public**
- Do NOT initialise with README (you'll upload files directly)
- Click **Create repository**

### 3. Upload the files
- On your new repo page, click **uploading an existing file**
- Upload ALL files maintaining the folder structure:
  - index.html
  - css/style.css
  - js/main.js
  - pages/about.html
  - pages/contact.html
- Commit with message: `Initial site launch`

### 4. Enable GitHub Pages
- Go to your repo **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Select branch: **main** · folder: **/ (root)**
- Click **Save**

### 5. Your site is live!
After ~2 minutes, your site will be live at:
`https://YOUR-USERNAME.github.io/recova-website/`

## Custom Domain (Optional)
If you want recova.ai or similar:
- Buy domain from Namecheap / Google Domains
- In GitHub Pages settings, add your custom domain
- Update DNS records at your registrar to point to GitHub Pages

## Updating the Site
Simply edit files and commit changes — GitHub Pages auto-deploys within minutes.
