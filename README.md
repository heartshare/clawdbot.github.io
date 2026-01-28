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
- **🎭 Animated Background** - Dynamic gradient background with patterns
- **📌 Sticky Header** - Header stays visible with scroll effects
- **✅ Fixed Scrolling** - Proper scroll positioning with header offset
- **🎯 Improved UI/UX** - Enhanced interactions, hover states, and transitions

### Platform Features
- **🧠 Smart AI** - Powered by advanced language models with customizable personas
- **🔌 Multi-Platform** - Connect to Telegram, WhatsApp, Discord, Slack, and more
- **⚡ Fast Response** - Low-latency responses with streaming support
- **🛠️ Extensible** - Build custom skills and tools
- **🔒 Secure** - Self-hosted with full control over your data
- **📱 Mobile Ready** - Responsive design for any device

## 🔧 UI/UX Improvements

### Scrolling Fixes
- **Fixed Header Overlap** - Content now properly accounts for sticky header
- **Scroll Offset** - Added `scroll-padding-top` to HTML for smooth navigation
- **Section Spacing** - `scroll-margin-top` on sections for proper anchor positioning
- **Smooth Scrolling** - Native smooth scrolling with proper offsets

### Enhanced Interactions
- **Improved Hover Effects** - Better feedback on all interactive elements
- **Button States** - Active states with scale effects
- **Menu Transitions** - Smooth sidebar toggle with cubic-bezier easing
- **Focus States** - Clear focus indicators for accessibility

### Mobile Optimizations
- **Overlay System** - Backdrop overlay for mobile sidebar
- **Touch-Friendly** - Larger tap targets on mobile
- **Responsive Header** - Hides non-essential buttons on small screens
- **Full-Width Sidebar** - Full-screen sidebar on mobile

### Visual Enhancements
- **Custom Scrollbars** - Always-visible, prominent scrollbars across entire site (12px width)
- **Blur Backdrops** - Modern backdrop-filter effects
- **Gradient Accents** - Subtle gradient backgrounds
- **Active States** - Visual feedback for active menu items
- **Non-Sticky Header** - Fixed header that doesn't overlap content

## 📋 Sidebar Menu Structure

The site features an organized sidebar with:

### Overview
- **Home** - Main landing page with hero section
- **Features** - 6 feature cards with detailed descriptions
- **Statistics** - Animated statistics display
- **Pricing** - 3 pricing plans with feature comparison
- **Use Cases** - 6 practical use case examples
- **Contact Us** - Contact form for inquiries

### Resources
- **Links** - External resources and documentation

### Community
- **GitHub** - Source code repository
- **Discord** - Community chat
- **Docs** - Documentation site
- **ClawdHub** - Skills marketplace

## 💰 Pricing Plans

### Free - $0/month
Perfect for personal use and small projects
- 1 platform integration
- 10 custom skills
- Community support
- Basic analytics

### Pro - $29/month
For power users and growing teams
- Unlimited platforms
- Unlimited skills
- Priority support
- Advanced analytics
- API access
- Custom branding

### Enterprise - $99/month
For organizations with advanced needs
- Everything in Pro
- Dedicated support
- SLA guarantee
- Custom integrations
- On-premise deployment
- Training & onboarding

## 📧 Contact Form

Users can reach out via contact form with:
- Name
- Email
- Subject
- Message

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

### GitHub Actions Workflow

The deployment is handled by `.github/workflows/deploy.yml` which:

1. **Triggers** on pushes to `main` branch
2. **Builds** static site (no build step needed for plain HTML/CSS)
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
- **Cards** - Clean borders with hover shadows and gradient top bar
- **Buttons** - Rounded corners, hover effects, and shadow
- **Sidebar** - Organized sections with icons and badges
- **Navigation** - Smooth scrolling with active states
- **Pricing Cards** - Featured plan highlighting and comparison
- **Contact Form** - Clean inputs with focus states
- **Header** - Sticky with blur backdrop and scroll effects
- **Animated Background** - Dynamic gradient with moving patterns

### Animations
- **Fade-in on scroll** - Content reveals as you scroll
- **Card hover effects** - Lift and shadow on hover
- **Gradient animations** - Rotating gradients on stat cards
- **Background patterns** - Subtle moving pattern overlay
- **Button interactions** - Smooth transitions and transforms

## ♿ Accessibility

- **Semantic HTML** - Proper use of semantic elements
- **ARIA Labels** - Screen reader support for interactive elements
- **Focus Indicators** - Clear focus states for keyboard navigation
- **Color Contrast** - WCAG AA compliant color ratios
- **Touch Targets** - Adequately sized touch targets on mobile

## 🔧 Built with Clawdbot

This project was created and deployed using Clawdbot automation.

## 📄 License

MIT License - feel free to use this site as a template for your own projects!

## 🔗 External Links

- [Clawdbot Repository](https://github.com/clawdbot/clawdbot)
- [Documentation](https://docs.clawd.bot)
- [Discord Community](https://discord.com/invite/clawd)
- [ClawdHub](https://clawdhub.com)
