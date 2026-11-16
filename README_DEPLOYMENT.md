# ALSKwela Elementary LS6 - GitHub Pages Deployment

App name: **Elementary ALS A&E Reviewer LS 6 - Digital Citizenship**  
Home Screen label: **Elem A&E LS6 Digital**

## Publish online

1. Create a new public GitHub repository called `alskwela-ls6-digital-reviewer-elementary`.
2. Unzip the deployment package on your computer. Upload the extracted files into the **root** of your repository, not inside an extra folder. Required files: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `.nojekyll`.
3. Commit on the `main` branch.
4. In **Settings > Pages**, choose **Deploy from a branch** and select `main` with `/(root)`.
5. Copy your HTTPS Pages link into the ALSKwela (Glide) Open Link action.

## Install and test offline (Android)

1. Open the Pages link directly in Chrome while online, not just in Glide's embedded view.
2. Refresh once and check for **Offline files saved successfully**.
3. Use Chrome's menu > **Install app** or **Add to Home Screen**. A Chrome shortcut may still function offline if cached.
4. Turn on airplane mode, open the Home Screen app/shortcut, take a practice trial and export a PDF report.
5. If caching fails, confirm all required files exist in the repository root; load online and refresh again.

## Student privacy and maintenance

The 90 items are embedded in index.html. Progress stays in the phone's browser storage; nothing is uploaded to a teacher dashboard. The PDF is generated locally. Do not clear site data or uninstall before downloading reports from unfinished trials. Teacher validation, item analysis, and real-device testing are required before release.

For future content updates, upload updated index.html and increment CACHE name in both index.html and sw.js. Keep the existing manifest ID and application name to retain the installed app identity.
