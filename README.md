# 🤖 Clawdbot - AI Assistant Platform

A powerful AI assistant platform for automation, intelligent conversations, and seamless integration across multiple platforms.

## 🌐 Live Site

**https://heartshare.github.io/clawdbot.github.io/**

## ✨ Features

### Design & UX
- **🎨 Shadcn-style UI** - Clean, minimal design with modern aesthetics
- **📱 Responsive Layout** - Mobile-first design that works on all devices
- **🌙 Dark Mode** - Theme toggle with localStorage persistence
- **🧭 Sidebar Navigation** - Collapsible sidebar with organized menu sections
- **🎬 Smooth Animations** - Fade-in effects on scroll
- **⚡ Fast Performance** - Optimized static site with instant loads

### Platform Features
- **🧠 Smart AI** - Powered by advanced language models with customizable personas
- **🔌 Multi-Platform** - Connect to Telegram, WhatsApp, Discord, Slack, and more
- **⚡ Fast Response** - Low-latency responses with streaming support
- **🛠️ Extensible** - Build custom skills and tools
- **🔒 Secure** - Self-hosted with full control over your data
- **📱 Mobile Ready** - Responsive design for any device

## 📋 Sidebar Menu Structure

The site features an organized sidebar with:

### Overview
- **Home** - Main landing page
- **Features** - 6 feature cards with detailed descriptions
- **Statistics** - Animated statistics display

### Resources
- **Use Cases** - 6 practical use case examples
- **Links** - External resources and documentation

### Community
- **GitHub** - Source code repository
- **Discord** - Community chat
- **Docs** - Documentation site
- **ClawdHub** - Skills marketplace

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

### GitHub Actions Workflow

The deployment is handled by `.github/workflows/deploy.yml` which:

1. **Triggers** on pushes to the `main` branch
2. **Builds** the static site (no build step needed for plain HTML/CSS)
3. **Deploys** to GitHub Pages using official Actions

### Deployment Process

```bash
# After making changes:
git add .
git commit -m "Your message"
git push origin main
```

The workflow automatically runs and deploys within 1-2 minutes.

## 📝 Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- JavaScript (Vanilla ES6+, no dependencies)
- Google Fonts (Inter)
- GitHub Actions
- GitHub Pages

## 🎨 Design System

The site uses a design system inspired by shadcn/ui:

### Color Palette
- **Primary:** #667eea (Purple gradient)
- **Background:** White / Dark (#09090b)
- **Foreground:** Black (#09090b) / White (#fafafa)
- **Border:** #e4e4e7 / Dark (#27272a)
- **Muted:** #f4f4f5 / Dark (#27272a)
- **Muted Foreground:** #71717a / Dark (#a1a1aa)

### Components
- **Cards** - Clean borders with hover shadows
- **Buttons** - Rounded corners, subtle hover effects
- **Sidebar** - Organized sections with icons
- **Navigation** - Smooth scrolling with active states

## 🔧 Built with Clawdbot

This project was created and deployed using Clawdbot automation.

## 📄 License

MIT License - feel free to use this site as a template for your own projects!

## 🔗 External Links

- [Clawdbot Repository](https://github.com/clawdbot/clawdbot)
- [Documentation](https://docs.clawd.bot)
- [Discord Community](https://discord.com/invite/clawd)
- [ClawdHub](https://clawdhub.com)
