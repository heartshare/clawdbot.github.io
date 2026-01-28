# 🤖 Clawdbot - AI Assistant Platform

A powerful AI assistant platform for automation, intelligent conversations, and seamless integration across multiple platforms.

## 🌐 Live Site

**https://heartshare.github.io/clawdbot.github.io/**

## ✨ Features

### Design & UX
- **🎨 Shadcn-style UI** - Clean, minimal design with modern aesthetics
- **📱 Responsive Layout** - Mobile-first design that works on all devices
- **🌙 Dark Mode** - Theme toggle with localStorage persistence
- **🧭 Mega Dropdown Navigation** - Top navigation with organized dropdown menus
- **🎬 Smooth Animations** - Fade-in effects on scroll
- **⚡ Fast Performance** - Optimized static site with instant loads
- **🎭 Animated Background** - Dynamic gradient background with patterns
- **📌 Fixed Header** - Header stays at top with blur backdrop
- **✅ Smooth Scrolling** - Proper scroll positioning with header offset
- **🎯 Improved UI/UX** - Enhanced interactions, hover states, and transitions

### Platform Features
- **🧠 Smart AI** - Powered by advanced language models with customizable personas
- **🔌 Multi-Platform** - Connect to Telegram, WhatsApp, Discord, Slack, and more
- **⚡ Fast Response** - Low-latency responses with streaming support
- **🛠️ Extensible** - Build custom skills and tools
- **🔒 Secure** - Self-hosted with full control over your data
- **📱 Mobile Ready** - Responsive design for any device

## 🧭 Navigation Structure

The site features a top mega dropdown navigation with:

### Top Navigation
- **Home** - Main landing page with hero section
- **Features** - Dropdown with 6 feature links (Smart AI, Multi-Platform, Fast Response, Extensible, Secure, Mobile Ready)
- **Pricing** - Direct link to pricing section
- **Use Cases** - Direct link to use cases section
- **Contact** - Direct link to contact form
- **Resources** - Dropdown with 4 resource links (GitHub, Documentation, Discord, ClawdHub)

### Mega Dropdown Menus
- **Features Dropdown** - Quick access to all features with icons
- **Resources Dropdown** - External resources with badges (GitHub with "New" badge)

### Mobile Navigation
- Full-screen mobile menu with organized sections
- Overlay backdrop when menu is open
- Close button for easy dismissal

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
- **Mega Dropdown** - Organized dropdowns with icons and sections
- **Navigation** - Smooth scrolling with active states
- **Pricing Cards** - Featured plan highlighting and comparison
- **Contact Form** - Clean inputs with focus states
- **Header** - Fixed with blur backdrop and mega dropdowns
- **Animated Background** - Dynamic gradient with moving patterns

### Animations
- **Fade-in on scroll** - Content reveals as you scroll
- **Card hover effects** - Lift and shadow on hover
- **Gradient animations** - Rotating gradients on stat cards
- **Background patterns** - Subtle moving pattern overlay
- **Button interactions** - Smooth transitions and transforms
- **Dropdown animations** - Smooth fade and slide effects
- **Arrow rotation** - Dropdown arrows rotate on hover

### Navigation Features
- **Mega Dropdowns** - Large dropdown menus with organized sections
- **Hover Triggers** - Dropdowns appear on hover
- **Icons & Badges** - Visual indicators and status badges
- **Active States** - Visual feedback for current section
- **Mobile Menu** - Full-screen navigation for mobile
- **Overlay System** - Backdrop overlay for mobile menu
- **Scroll Spy** - Active menu updates on scroll

### Visual Enhancements
- **Custom Scrollbars** - Always-visible, prominent scrollbars across entire site (12px width)
- **Blur Backdrops** - Modern backdrop-filter effects
- **Gradient Accents** - Subtle gradient backgrounds
- **Active States** - Visual feedback for active menu items
- **Fixed Header** - Header stays at top without overlapping content
- **Back to Top Button** - Floating button at bottom right for quick navigation

### Mobile Optimizations
- **Full-Screen Menu** - Mobile navigation takes full screen
- **Overlay System** - Backdrop overlay when menu is open
- **Touch-Friendly** - Larger tap targets and better spacing
- **Responsive Header** - Hides non-essential buttons on small screens
- **Close Button** - Easy-to-close button on mobile menu

### Desktop Navigation
- **Top Mega Menu** - Dropdown menus that appear on hover
- **Organized Sections** - Dropdowns have clear section dividers
- **Icons & Badges** - Visual elements for quick recognition
- **Smooth Transitions** - Elegant animations for all interactions

## ♿ Accessibility

- **Semantic HTML** - Proper use of semantic elements
- **ARIA Labels** - Screen reader support for interactive elements
- **Focus Indicators** - Clear focus states for keyboard navigation
- **Color Contrast** - WCAG AA compliant color ratios
- **Touch Targets** - Adequately sized touch targets on mobile
- **Keyboard Navigation** - All menus accessible via keyboard
- **Skip Links** - Skip to content for screen readers

## 🔧 Built with Clawdbot

This project was created and deployed using Clawdbot automation.

## 📄 License

MIT License - feel free to use this site as a template for your own projects!

## 🔗 External Links

- [Clawdbot Repository](https://github.com/clawdbot/clawdbot)
- [Documentation](https://docs.clawd.bot)
- [Discord Community](https://discord.com/invite/clawd)
- [ClawdHub](https://clawdhub.com)
