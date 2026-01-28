# Clawdbot Website

A static website for Clawdbot documentation and information.

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

- **Repository:** https://github.com/heartshare/clawdbot.github.io
- **Live Site:** https://heartshare.github.io/clawdbot.github.io/

## 📝 Tech Stack

- HTML5
- CSS3
- GitHub Actions
- GitHub Pages

## 🤖 Deployment Details

### GitHub Actions Workflow

The deployment is handled by `.github/workflows/deploy.yml` which:

1. **Triggers** on pushes to the `main` branch
2. **Builds** the static site (no build step needed for plain HTML/CSS)
3. **Deploys** to GitHub Pages using the official Actions

### Deployment Process

```bash
# After making changes:
git add .
git commit -m "Your message"
git push origin main
```

The workflow automatically runs and deploys within 1-2 minutes.

## 🔧 Built with Clawdbot

This project was created and deployed using Clawdbot automation.
