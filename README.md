# easyLogin™ | 2FA Authenticator

A lightweight, privacy-focused TOTP 2FA code generator with a premium dark UI. No signup required, works 100% client-side.

## Features

- ✨ **Instant TOTP generation** from Base32 secrets
- 🎨 **FastAccs Dark Theme** - Premium, minimal UI
- 🔒 **Privacy-first** - Everything runs in your browser
- 📱 **Mobile-optimized** - Works perfectly on all devices
- ⏱️ **Live countdown** with auto-refresh
- 🔐 **Secret masking** - Your keys stay private
- ✅ **Smart validation** - Real-time input checking

## Usage

### Method 1: Direct URL
```
https://your-site.netlify.app/#YOUR_SECRET_KEY
```

### Method 2: Manual Entry
1. Open the site
2. Paste your Base32 secret (A-Z, 2-7)
3. Click **GENERATE**
4. Copy your 6-digit code

## Quick Deploy

### Netlify
```bash
# Add to _redirects file:
/*    /index.html   200
```

### Any Static Host
Upload these files:
- `index.html`
- `fa-style.css`
- `_redirects` (optional)

## Tech Stack

- Pure HTML/CSS/JavaScript
- [otplib](https://github.com/yeojz/otplib) for TOTP
- DM Sans & Open Sans fonts
- No frameworks, no build step

## Design System

Built with the **FastAccs Dark Theme** style guide:
- Neon green CTAs (#05D471)
- Dark premium background
- Subtle depth & glassmorphism
- 180ms transitions
- 4px spacing grid

## License

MIT

---

**Made by [teerex](https://www.rottenlibrary.net) 🦖**
# LogsFormatter
