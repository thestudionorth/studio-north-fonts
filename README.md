# Studio North Fonts (GitHub Pages)

This repo serves your custom **Studio North** font like Google Fonts via a simple `<link>`.

## Files to include
- `StudioNorth-Bold.woff2` (required)
- `StudioNorth-Bold.woff` (optional fallback)
- `studio-north-font.css` (already provided)
- `index.html` (demo page)
- `.nojekyll` (so Pages serves files as-is)

> **Note:** Do not commit font files unless you have the license rights to self-host them.

## Quick start (GitHub Pages)
1. Create a GitHub repo named **`studio-north-fonts`**.
2. Upload the files above (drag & drop in the web UI).
3. Go to **Settings → Pages** → set **Branch** to `main` and **Folder** to `/root`, then **Save**.
4. Wait ~1 minute. Your page will be live at:
   ```
   https://<your-username>.github.io/studio-north-fonts/
   ```
5. Your embed link becomes:
   ```html
   <link rel="stylesheet" href="https://<your-username>.github.io/studio-north-fonts/studio-north-font.css">
   ```

## Optional: Custom domain (fonts.thestudionorth.com)
1. Add a **CNAME** record in your DNS:
   - **Name**: `fonts`
   - **Target/Value**: `<your-username>.github.io`
2. In the repo, create a file named `CNAME` containing:
   ```
   fonts.thestudionorth.com
   ```
3. In **Settings → Pages**, enable your custom domain and enforce HTTPS.
4. Now your embed link is:
   ```html
   <link rel="stylesheet" href="https://fonts.thestudionorth.com/studio-north-font.css">
   ```

## Using the font
```css
h1, h2, h3 { font-family: 'Studio North', sans-serif; font-weight: 700; }
```

## Tip: Versioning
Tag releases (e.g., `v1.0.0`) and optionally use jsDelivr CDN:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/<your-username>/studio-north-fonts@v1.0.0/studio-north-font.css">
```
