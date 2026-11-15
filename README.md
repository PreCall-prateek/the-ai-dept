# JARVIS Intelligence Official Website

Static, mobile-friendly website files for GitHub Pages. The site uses no build step, external fonts, analytics scripts, or tracking pixels.

## Before publishing

1. Open `index.html`, `privacy.html`, and `terms.html` in VS Code.
2. Replace every `REPLACE_WITH_TELEGRAM_CHANNEL` with your public Telegram channel username (without `@`). Example: if the channel is `https://t.me/jarvis_updates`, replace the placeholder with `jarvis_updates`. The “Download JARVIS” buttons will open that channel. If you use a private invite link, replace the whole `https://t.me/REPLACE_WITH_TELEGRAM_CHANNEL` URL in each button with the full invite link.
3. Replace every `REPLACE_WITH_SUPPORT_EMAIL` with an email address you control.
4. Review the privacy policy against the exact services and permissions in the APK you publish. Update the date and any statements that changed.
5. Keep the notification activation card marked “planned” until that control is implemented and included in a released APK.

## Publish to your existing GitHub Pages site

Your existing site is `precall-prateek/jarvis-intelligence-legal`. In GitHub, open that repository, choose **Add file → Upload files**, upload the contents of this folder (not the outer folder itself), and commit the changes to the publishing branch. GitHub Pages should keep using the repository's existing settings.

The expected site links are:

- `https://precall-prateek.github.io/jarvis-intelligence-legal/`
- `https://precall-prateek.github.io/jarvis-intelligence-legal/privacy.html`
- `https://precall-prateek.github.io/jarvis-intelligence-legal/terms.html`

## What to add to Telegram later

Publish the signed APK as a Telegram channel post. Include the version number, release date, required Android version if known, and a SHA-256 checksum. Keep the signing key private and keep a backup outside the public repository.

## Important

The privacy and terms pages are a product-specific starting draft, not legal advice. Confirm the developer contact and review the text for your country, service settings, and final app build before publishing.
