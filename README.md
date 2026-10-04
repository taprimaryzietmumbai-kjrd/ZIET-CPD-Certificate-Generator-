# ZIET Mumbai — Certificate Generator

GitHub Pages front-end/access portal for the existing ZIET Mumbai Certificate Generator.

## Deploy

1. Create a GitHub repository, e.g. `certificate-generator`.
2. Upload `index.html` and `style.css` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.
7. GitHub will provide the Pages URL.

The existing Google Apps Script is not modified.

## Current destination

The button currently opens the supplied Certificate Generator `/exec` URL.

## Dynamic QR architecture

For a genuinely dynamic QR, the QR should point to a stable redirect URL rather than directly to the Apps Script URL. This GitHub page can be used as a stable access layer, but changing the final destination requires changing the page code and redeploying. For a truly destination-editable QR without reprinting, use a stable redirect endpoint whose target can be updated independently.
