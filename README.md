# The Boss Tailor — deployable website

This folder is ready for static hosting such as GitHub Pages, Netlify, Cloudflare Pages, or any ordinary web server.

## What works without a backend
- Men/Women collection filters
- Product gallery modal with multiple views
- Phone links (`tel:`)
- WhatsApp links
- Google Maps / Google Reviews links
- Booking form: it prepares a WhatsApp message containing the visitor's form details and opens WhatsApp to The Boss Tailor

No form data is stored by the site itself.

## Publish with GitHub Pages
1. Create a new GitHub repository, for example `tailortheboss`.
2. Upload the **contents** of this folder to the repository root (`index.html`, `assets/`, `.nojekyll`, etc.).
3. In GitHub open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. GitHub will provide a live URL such as `https://USERNAME.github.io/tailortheboss/`.

Because all asset paths in the site are relative, it works correctly when hosted inside a GitHub Pages repository path.

## Real contact actions currently configured
- Phone / WhatsApp: +66 911 051 152
- Hours shown: 9:00 - 21:00 daily
- Google Maps / Reviews links open externally

## Before production launch
Use only images/content you have permission to publish, and if you later want bookings saved to a database or emailed automatically, connect the form to a real backend/form service. The current WhatsApp booking flow works on static hosting and does not require one.
