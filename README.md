# Mosaic Launcher website

A static, mobile-friendly website for GitHub Pages. No build process or dependencies required.

## Deploy
1. Create a GitHub repository named `mosaic-website` and upload all files in this folder (keep folders intact).
2. In GitHub repository **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. The initial website will appear at `https://YOUR_USERNAME.github.io/mosaic-website/`.
4. For `mosaic.globin.dev`, set the custom domain in **Settings → Pages** and configure a DNS CNAME record: host `mosaic` → `YOUR_USERNAME.github.io` (without the repository path). Wait for DNS/HTTPS verification, then enable **Enforce HTTPS** when available.
5. After the custom domain is configured, keep the `CNAME` file in the repository. Replace its content if your domain differs.

## Before publishing
- Replace every `[placeholder]` in the privacy policy, terms, and support pages.
- Verify privacy disclosures against the actual release build, SDKs, permissions, storage, analytics, billing and Play Store Data Safety.
- Replace the illustrative Home screen with real screenshots when available.
- Replace the 'Coming to Android' call-to-action with the real Google Play URL once live.
- Update changelog with real release notes; avoid claiming unshipped features.
- Customize `assets/logo.svg` and `favicon.svg` if your final icon changes.

## Pages
`index.html`, `privacy.html`, `terms.html`, `support.html`, `changelog.html`.
