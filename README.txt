═══════════════════════════════════════════
  URJAA MINDZ — PRODUCTION WEBSITE
  Version 2.0 | Ready for Deployment
═══════════════════════════════════════════

WEBSITE PAGES (7 + Admin)
─────────────────────────
  index.html       → Home page
  programs.html    → Programs, Age Selector & Toolkit (merged)
  community.html   → Community Hub, Workshops & Chat
  contact.html     → Contact form
  story.html       → Our Story
  privacy.html     → Privacy Policy
  terms.html       → Terms of Service

ADMIN PANEL
───────────
  admin.html       → Content management system
  URL: yoursite.com/admin.html

  Login credentials (prefilled for testing):
  ┌─────────────────────────────────┐
  │  Username : Urjaa_Admin         │
  │  Password : Admin1234           │
  └─────────────────────────────────┘

  ⚠️  Remove prefilled credentials before
      going live in production!

REQUIRED FILES
──────────────
  logo.png          → Brand logo (transparent background)
  tailwind.min.css  → CSS framework (must be in same folder)
  tailwind_min.css  → CSS framework (backup name)

DEPLOYMENT (Vercel / Netlify / GitHub Pages)
────────────────────────────────────────────
  1. Upload this entire folder
  2. Deploy — no build step needed
  3. Your site is live!

  For GitHub Pages:
  1. Push to a GitHub repository
  2. Settings → Pages → Source: main branch
  3. Your site is live at username.github.io/repo-name

FEATURES
────────
  ✓ Glassmorphism design with warm cream/gold theme
  ✓ Responsive — mobile, tablet, desktop
  ✓ Join Now popup (name + WhatsApp number collection)
  ✓ Admin panel with session-based authentication
  ✓ PDF upload/download pipeline via admin
  ✓ Workshop registration system
  ✓ Program popup system with admin-editable content
  ✓ Analytics dashboard with demo data
  ✓ Live Workshops section on Community page
  ✓ Sensory Play Guides & Articles (Toolkit merged into Programs)

SOCIAL LINKS
────────────
  Instagram: https://www.instagram.com/urjaa.mom.diaries
  Facebook:  https://www.facebook.com/share/19iVtFJMzK/
  WhatsApp:  +91 9529190553
  Email:     urjjakids@gmail.com

BACKEND SETUP (Optional)
────────────────────────
  The Join Now form currently sends data via fetch() to:
  1. Google Sheets webhook (replace APPS_SCRIPT_ID in code)
  2. CallMeBot WhatsApp API (replace YOUR_API_KEY in code)

  Until configured, the form shows success but data
  is not delivered. See submitJoinForm() in any HTML file.

BRAND SPECS
───────────
  Primary:   #7c6100 (gold-brown)
  Secondary: #a74632 (rust red)
  Accent:    #fccc38 (gold)
  Fonts:     Noto Serif + Plus Jakarta Sans
  Tagline:   स्नेहेन वर्धते बुद्धिः
             (Wisdom grows through love)

© 2025 Urjaa Mindz. स्नेहेन वर्धते बुद्धिः
