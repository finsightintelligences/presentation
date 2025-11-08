# FinSight Intelligence Landing Page

A professional, responsive landing page for FinSight Intelligence - your AI-powered financial analytics platform.

## What's Included

- `index.html` - Main landing page
- `styles.css` - All styling (mobile responsive)
- `script.js` - Interactive features and smooth scrolling
- `netlify.toml` - Netlify deployment configuration

## How to Deploy to Netlify

### Option 1: Drag and Drop (Easiest)

1. Go to [Netlify](https://app.netlify.com)
2. Sign up or log in
3. Click "Add new site" → "Deploy manually"
4. Drag and drop this entire folder into the deployment area
5. Done! Your site is live

### Option 2: GitHub Deployment (Recommended for Updates)

1. Create a new repository on GitHub
2. Upload all these files to your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```
3. Go to Netlify and click "Add new site" → "Import an existing project"
4. Connect your GitHub account
5. Select your repository
6. Netlify will automatically detect the settings and deploy

### Option 3: Netlify CLI

1. Install Netlify CLI: `npm install -g netlify-cli`
2. Navigate to this folder in your terminal
3. Run: `netlify deploy`
4. Follow the prompts
5. For production: `netlify deploy --prod`

## Customization

### Update Content
- Edit `index.html` to change text, links, or structure
- Modify `styles.css` to adjust colors, fonts, and layout
- Update `script.js` to add more interactive features

### Change Colors
The main color scheme uses:
- Primary: `#2563eb` (blue)
- Accent: `#fbbf24` (yellow/gold)
- Gradient: `#667eea` to `#764ba2` (purple gradient)

Search for these hex codes in `styles.css` to change the color scheme.

### Add Your Logo
Replace the text in the navigation with an image:
```html
<div class="nav-brand">
    <img src="your-logo.png" alt="FinSight Intelligence">
</div>
```

### Connect Email Form
Replace the form submission in `script.js` with your actual backend API or email service (like Formspree, Netlify Forms, or your own API).

## File Structure
```
finsight-landing/
├── index.html          # Main page
├── styles.css          # Styling
├── script.js           # Interactivity
├── netlify.toml        # Netlify config
└── README.md           # This file
```

## Features

✅ Fully responsive (mobile, tablet, desktop)
✅ Modern gradient design
✅ Smooth scroll navigation
✅ Animated elements on scroll
✅ SEO-friendly structure
✅ Fast loading
✅ Professional design

## Support

For issues or questions about deployment, check:
- [Netlify Documentation](https://docs.netlify.com)
- [Netlify Support](https://support.netlify.com)

## License

Feel free to customize this landing page for your business needs.
