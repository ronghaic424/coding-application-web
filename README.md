# AI Cleanup static website

This directory contains the public website for AI Cleanup for iOS. It is written in plain HTML and CSS for users and Google OAuth reviewers.

No package installation, Node.js server, database or build command is required. Open `index.html` directly in a browser or upload this directory to any static web host.

## Pages

- `index.html` — product homepage and Google OAuth purpose
- `gmail-data.html` — complete Google user-data disclosure
- `privacy.html` — privacy policy
- `terms.html` — terms of use
- `support.html` — support and Google access-revocation guidance
- `styles.css` — shared responsive styling
- `public/` — app icon, favicon and social image

## Google OAuth verification handoff

Deploy the complete directory to a domain owned by CODING APPLICATION and verify that domain in Google Search Console. The website, OAuth consent screen and iOS app must use the exact product name `AI Cleanup`, the same app icon and the same Gmail behavior.

Configure Google Auth Platform with these public URLs after replacing the example domain:

- App home page: `https://your-domain.example/index.html`
- Privacy policy: `https://your-domain.example/privacy.html`
- Terms of service: `https://your-domain.example/terms.html`
- Detailed Gmail disclosure: `https://your-domain.example/gmail-data.html`
- User support: `https://your-domain.example/support.html`

Do not upload the downloaded Google configuration plist or any client secret. Gmail authorization occurs only inside the AI Cleanup iOS app; this website does not receive Gmail data.

Support contact: `coding_application@protonmail.com`.
