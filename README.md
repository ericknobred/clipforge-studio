# ClipForge Studio legal pages (GitHub Pages)

Static pages for the Google OAuth and TikTok app forms: `index.html`, `privacy.html`, `terms.html`.

1. Replace `[YOUR EMAIL]` and `[DATE]` in the three HTML files.
2. Create a **public** GitHub repository (for example `clipforge-studio-legal`) and upload the
   three `.html` files to its root (not this README, which is only for you).
3. Repository **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`.
4. After a minute the pages are at
   `https://YOUR-USER.github.io/clipforge-studio-legal/` (`privacy.html`, `terms.html`).
5. TikTok URL verification: add the URL prefix
   `https://YOUR-USER.github.io/clipforge-studio-legal/`, download the signature file TikTok gives you
   and upload it to the **same repository root**, so it opens at
   `https://YOUR-USER.github.io/clipforge-studio-legal/<file-name>`. Then press Verify.
6. Use these URLs in the TikTok app (Terms, Privacy, web/desktop URL) and in the Google Cloud
   Branding page (home page, privacy policy, terms).

If TikTok refuses `github.io`, point a domain you own at GitHub Pages (Settings → Pages → Custom
domain) and verify the domain with a DNS TXT record instead.
