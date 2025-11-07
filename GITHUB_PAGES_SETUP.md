# GitHub Pages Setup Guide

This guide will help you deploy the interactive visualizations and architecture explorer to GitHub Pages.

## 🚀 Quick Setup (5 minutes)

### Step 1: Push to GitHub

```bash
# Initialize git repository (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Microsoft Entra ID Learning Program"

# Create repository on GitHub (go to github.com/new)
# Then add remote and push
git remote add origin https://github.com/YOUR-USERNAME/entra_id_learning.git
git branch -M main
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings**
3. Scroll down to **Pages** (in the left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 3: Update Configuration

Edit `_config.yml` and replace placeholders:

```yaml
# Replace [username] with your GitHub username
url: "https://YOUR-USERNAME.github.io"
baseurl: "/entra_id_learning"

# Add your information
author: Your Name
email: your.email@example.com
github_username: YOUR-USERNAME
```

Also update in `index.html`:
- Line 74: Replace `[username]` with your GitHub username
- Line 224: Replace `[username]` with your GitHub username

### Step 4: Wait for Deployment

- GitHub Pages typically deploys in 1-2 minutes
- Check deployment status under **Actions** tab
- Your site will be available at: `https://YOUR-USERNAME.github.io/entra_id_learning/`

## 📁 What Gets Published

Your GitHub Pages site includes:

### 🏠 Landing Page (`index.html`)
**URL**: `https://YOUR-USERNAME.github.io/entra_id_learning/`

Features:
- Program overview
- Learning path options
- Quick navigation to all resources
- Beautiful responsive design

### 🏗️ Architecture Explorer (`architecture.html`)
**URL**: `https://YOUR-USERNAME.github.io/entra_id_learning/architecture.html`

Features:
- Interactive Mermaid diagrams
- 7 architecture layers
- Clickable navigation
- The 10 Commandments of Entra ID

### 📅 Interactive Schedule (`labs/schedule-timeline.html`)
**URL**: `https://YOUR-USERNAME.github.io/entra_id_learning/labs/schedule-timeline.html`

Features:
- Visual timeline of all 6 days (pre-work + 5 days)
- Progress tracking with checkboxes
- Local storage persistence
- Export progress as JSON
- Expandable module details

### 📚 Documentation Files

All markdown files in `docs/` are accessible:
- `docs/Entra-ID-5-Day-Schedule.md`
- `docs/Entra-ID-Enterprise-Architecture-Guide.md`
- `docs/Entra-ID-Resource-Links.md`

## 🎨 Customization

### Change Color Scheme

Edit the CSS in each HTML file. The main gradient uses:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Replace `#667eea` and `#764ba2` with your preferred colors.

### Add Google Analytics

Add to `<head>` section of HTML files:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Custom Domain

1. Add `CNAME` file to repository root with your domain:
   ```
   learning.yourdomain.com
   ```

2. In GitHub Settings > Pages:
   - Enter custom domain
   - Enable "Enforce HTTPS"

3. Configure DNS:
   - Add CNAME record pointing to `YOUR-USERNAME.github.io`

## 🔧 Troubleshooting

### Pages not updating?
- Check **Actions** tab for build errors
- Wait 2-5 minutes after pushing changes
- Hard refresh browser (Ctrl+Shift+R or Cmd+Shift+R)

### 404 errors?
- Verify `baseurl` in `_config.yml` matches repository name
- Check file paths are correct (case-sensitive)
- Ensure files are committed and pushed

### Diagrams not rendering?
- Check browser console for errors
- Verify Mermaid.js CDN is accessible
- Try different browser

## 🚀 Advanced Features

### Add Jekyll Blog

Create `_posts/` directory:
```bash
mkdir _posts
```

Add blog post: `_posts/2025-11-07-day-1-complete.md`
```markdown
---
layout: post
title: "Completed Day 1: Foundations"
date: 2025-11-07
---

Today I completed Day 1 of the Entra ID learning program...
```

### Add Progress Sharing

Add social sharing to schedule timeline:
```html
<button onclick="shareProgress()">Share Progress</button>

<script>
function shareProgress() {
    const text = `I've completed ${completedModules.size} modules in the Microsoft Entra ID Learning Program!`;
    if (navigator.share) {
        navigator.share({ title: 'My Learning Progress', text: text });
    } else {
        // Fallback: copy to clipboard
        navigator.clipboard.writeText(text);
        alert('Progress copied to clipboard!');
    }
}
</script>
```

### Add Comments

Add Disqus or giscus for comments on documentation pages.

## 📊 Analytics & Tracking

### View GitHub Pages Analytics

GitHub doesn't provide built-in analytics. Options:
1. **Google Analytics** (most popular)
2. **Plausible** (privacy-friendly)
3. **Simple Analytics** (paid, privacy-focused)

### Track Learning Progress

The schedule timeline saves progress to localStorage. To sync across devices:
1. Use Firebase or Supabase for backend
2. Implement user authentication
3. Store progress in cloud database

## 🎓 Share Your Site

Once deployed, share your learning journey:

### Social Media Templates

**Twitter/X**:
```
🚀 Just started the Microsoft Entra ID Learning Program!

📅 5-day intensive training
🔐 Zero Trust security
🏗️ Enterprise architecture

Check it out: https://YOUR-USERNAME.github.io/entra_id_learning/

#MicrosoftEntra #IdentityManagement #CloudSecurity
```

**LinkedIn**:
```
Excited to share my learning journey with Microsoft Entra ID!

I'm following a comprehensive 5-day program covering:
✅ Identity fundamentals
✅ MFA & Conditional Access
✅ Enterprise SSO integration
✅ Identity governance & PIM
✅ Production architecture design

Track my progress: https://YOUR-USERNAME.github.io/entra_id_learning/

#IdentityAndAccess #MicrosoftEntra #CloudSecurity #ProfessionalDevelopment
```

## 🤝 Contributing

Want to improve the visualizations or add features?

1. Fork the repository
2. Create feature branch
3. Make improvements
4. Submit pull request

Ideas for contributions:
- Additional interactive diagrams
- Quiz system for each day
- Video integration
- Mobile app version
- Integration with Microsoft Learn progress

## 📝 License

This learning program is free to use and share. Attribution appreciated but not required.

---

## ✅ Checklist

Before deploying:
- [ ] Repository pushed to GitHub
- [ ] GitHub Pages enabled in settings
- [ ] `_config.yml` updated with your username
- [ ] `index.html` updated with your username
- [ ] Site accessible at GitHub Pages URL
- [ ] All links working correctly
- [ ] Mobile responsive design verified
- [ ] Shared on social media (optional)

**Your site should be live at**: `https://YOUR-USERNAME.github.io/entra_id_learning/`

Enjoy your learning journey! 🎓
