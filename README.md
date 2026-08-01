# D9 Skincare — Trade Fair Registration Form

🔗 **Live site:** [prodermsurvey.netlify.app](https://prodermsurvey.netlify.app)

A simple QR-code registration form for D9 Skincare's trade fair booth. Visitors scan a QR code, fill in their details, and select a product they'd like a sample of. Submissions are captured live via Netlify Forms and can be downloaded as a CSV/Excel file anytime.

## What it captures
- Full Name
- Mobile Number (10-digit validated)
- City
- Product Interest (dropdown, with "Other" option)

## Tech stack
Plain HTML/CSS/JS — no build tools, no frameworks. Form submissions are handled by **Netlify Forms** (`data-netlify="true"` on the `<form>` tag).

## How to edit
1. Open `index.html` in VS Code
2. Make your changes
3. Save (Ctrl+S)
4. Push to deploy:
   ```bash
   git add .
   git commit -m "Describe your change here"
   git push
   ```
5. Netlify auto-deploys within ~30 seconds. Hard refresh the live site (Ctrl+Shift+R) to see changes.

## To update the logo
Replace `images/logo.png` with a new file (keep the same filename), or update the `src` path in the `<img class="mark-dot">` tag if using a different filename.

## To check submissions
Go to the Netlify dashboard → **Forms** tab → view live entries or click **Download CSV**.
