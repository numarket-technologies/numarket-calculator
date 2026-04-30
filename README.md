# NuMarket Pricing Calculator

Interactive pricing and profitability calculator for NuMarket's data intelligence business.

## Features
- 3 service tiers (Insight, Operate, Command)
- Full cost modeling (platform, labor, overhead)
- Break-even analysis
- 12-36 month growth projections
- Client pricing recommendations

## Live Demo
View at: https://YOUR-USERNAME.github.io/numarket-calculator/

## Setup Instructions

### Option 1: Quick GitHub Pages Setup

1. **Create a new repository on GitHub**
   - Go to https://github.com/new
   - Name it: `numarket-calculator`
   - Make it Public
   - Don't initialize with README
   - Click "Create repository"

2. **Upload files**
   - Click "uploading an existing file"
   - Drag and drop these 3 files:
     - `index.html`
     - `numarket-pricing-calculator.jsx`
     - `README.md`
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
   - Click Save
   - Wait 1-2 minutes

4. **Access your calculator**
   - Visit: `https://YOUR-USERNAME.github.io/numarket-calculator/`

### Option 2: Using Git (Command Line)

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit - NuMarket pricing calculator"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/numarket-calculator.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow step 3 above to enable GitHub Pages.

## Local Development

Open `index.html` directly in your browser - no build process needed!

## Technologies
- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Lucide React icons (via CDN)
