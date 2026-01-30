# IntelliWatch Landing Page - Deployment Guide

## ✅ Your buttons are now enhanced with:
- 🎨 Beautiful gradient backgrounds
- ✨ Smooth hover animations with scale and lift effects
- 💫 Pulsing glow effect on the main CTA
- ➡️ Arrow animations that slide on hover
- 🌊 Ripple click effects
- 🔥 Extra prominent submit button with green gradient

## 🚀 Deployment Options

### Option 1: Surge (Recommended for Quick Deploy)

The issue you encountered is due to permission restrictions. Here's the solution:

```bash
# First, remove the CNAME file I created
rm CNAME

# Then try surge without specifying a domain
cd /Users/bhurvasharma/intelliwatch-landing
surge
```

When prompted, **press Enter** to accept the random domain Surge generates. Don't type a custom domain.

### Option 2: Vercel (Most Popular)

```bash
# Install Vercel globally
npm install -g vercel@latest

# Deploy (will open browser for auth)
cd /Users/bhurvasharma/intelliwatch-landing
vercel --prod
```

### Option 3: Netlify Drop (No CLI needed!)

1. Go to https://app.netlify.com/drop
2. Drag and drop your `intelliwatch-landing` folder
3. Get instant deployment!

### Option 4: GitHub Pages (Free & Reliable)

```bash
# 1. Initialize git repo
cd /Users/bhurvasharma/intelliwatch-landing
git init
git add .
git commit -m "Initial commit: IntelliWatch landing page"

# 2. Create GitHub repo (you'll need to do this on github.com)
# Then push:
git remote add origin https://github.com/YOUR_USERNAME/intelliwatch-landing.git
git branch -M main
git push -u origin main

# 3. Go to repo Settings > Pages > Source: main branch
# Your site will be live at: https://YOUR_USERNAME.github.io/intelliwatch-landing/
```

### Option 5: Python HTTP Server (Local Testing)

Your site is now running locally at:
**http://localhost:8080**

To deploy, use one of the options above.

## 📦 What's Included

### Files:
- `index.html` - Main landing page
- `styles.css` - Enhanced button styles with animations
- `script.js` - Interactive features and ripple effects  
- `README.md` - Documentation
- `CNAME` - (Remove this before deploying)

### Features:
✨ Gradient buttons with glow effects
✨ Animated arrows on hover
✨ Ripple click animations
✨ Pulse effect on primary CTA
✨ Smooth transitions and transforms
✨ Mobile responsive design

## 🎯 Quick Deploy Command

**For Surge (after removing CNAME):**
```bash
rm CNAME && surge
```

Just press Enter when it asks for domain!

## 🌐 Your Local Site

Currently running at: http://localhost:8080
Open this in your browser to see the enhanced buttons!

---

**Note:** The enhanced buttons now have:
- Purple gradient with white text
- Smooth scale and lift on hover
- Arrow slides right on hover
- Ripple effect on click
- Green gradient for submit button
- Pulsing glow effect on main CTA