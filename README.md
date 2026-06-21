# Sova — Landing Page

Marketing site for **Sova**, an iOS-first AI prank-video app ("Turn ideas and photos into AI videos
in seconds"). Static HTML + CSS, no build step, no dependencies.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page (hero, features, how-it-works, showcase, FAQ, CTA) |
| `privacy.html` | Privacy Policy (template — review with legal counsel) |
| `terms.html` | Terms of Service (template — review with legal counsel) |
| `styles.css` | Shared design tokens + components (brand colors from the app mockups) |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is (no Jekyll processing) |

## Brand

Three colors only, matching the app:

- Background `#131313`
- Accent / highlight `#96E4F8`
- CTA / secondary `#E6F9FE`

Apple system font stack, solid colors (no gradients except the card-bottom scrim), rounded cards,
one clear CTA per section.

## Before going live — replace these placeholders

- `[Company Name]`, `[Company Address]`, `[Governing jurisdiction]`, `[Effective date]` in
  `privacy.html` and `terms.html`.
- Contact email `hello@sova.app` (used in the footer and legal pages) — swap for your real address.
- The App Store download buttons link to `#` — point them at your App Store URL once the app is live.
- The legal pages are a starting **template**; have them reviewed by qualified legal counsel.

## Run locally

Just open the files in a browser:

```sh
open index.html
```

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source = Deploy from a branch**.
4. Choose branch **`main`** and folder **`/ (root)`**, then **Save**.
5. After it builds, your pages will be available at:
   - `https://<username>.github.io/<repo>/`
   - `https://<username>.github.io/<repo>/privacy.html`
   - `https://<username>.github.io/<repo>/terms.html`

Use the privacy and terms URLs in App Store Connect.
