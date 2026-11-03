# Elitez Indonesia website: id.elitez.ai

Live site: https://id.elitez.ai/ · Owner: Adam Tirta, Country Director

## How to update the website
1. Open `site/index.html` here on GitHub and click the pencil (Edit).
2. Change the text and click **Commit changes** (keep "Commit directly to the `main` branch").
3. Within about 1–2 minutes the change is live at id.elitez.ai and you get an email confirming it.
   If a browser still shows the old page, hard-refresh (Ctrl/Cmd + Shift + R).

Everything inside the `site/` folder is published. Files outside it (this README, `package.json`, `wrangler.jsonc`) are not.

## What's where
- `site/index.html`: the whole website (text, sections, forms)
- `site/favicon.png`, `site/og-image.png`: tab icon and the WhatsApp/LinkedIn link-preview image
- `site/robots.txt`, `site/sitemap.xml`: search engines

## Good to know
- The Hire Talent, Submit CV and Contact forms email Adam directly; nothing is stored.
- The site is light-theme only. A change containing a dark-mode rule (`prefers-color-scheme: dark`) is **not published** and Derrick is emailed the reason.
- If a change fails the live check it is rolled back automatically and the previous version stays up.
