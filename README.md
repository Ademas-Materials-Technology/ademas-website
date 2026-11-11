# EthioCeram Materials & Technology website

Responsive bilingual (English/Amharic) static website with six sections: Home, About, Services, Research, Resources, Contact.

## Before publishing
1. Open `script.js` and replace `YOUR_EMAIL@example.com` in `BUSINESS_EMAIL` with your real contact email.
2. Check all business descriptions, particularly licensing, qualifications, and project status.
3. The inquiry form uses `mailto:` to open the visitor's email application. It does **not** automatically deliver a message, and may not work if the visitor has no configured email application. For server-delivered forms later, connect a form backend (e.g. Netlify Forms or Formspree) and add a privacy notice.
4. Business name and domain availability have **not** been verified.

## Preview locally
Open `index.html` in a browser. Or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish for free (GitHub Pages)
1. Create a GitHub account and a new public repository.
2. Upload `index.html`, `styles.css`, `script.js`, and `favicon.svg` to the repository root.
3. Open Settings > Pages > Build and deployment > Deploy from a branch; select main and / (root).
4. Wait for GitHub to show the public website URL. HTTPS is supported for GitHub Pages sites.

## Alternative: Cloudflare Pages
Create a Pages project and upload the folder using direct upload. Set the output directory to the folder containing `index.html`.

No build tools or external JavaScript dependencies are needed.
