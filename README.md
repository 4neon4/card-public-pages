# Card public pages

Static public pages for App Store Connect:

- `privacy.html` - Privacy Policy URL
- `support.html` - Support URL
- `index.html` - simple landing page

## Fastest publishing option

Use Netlify Drop:

1. Open https://app.netlify.com/drop
2. Drag the whole `card-public-pages` folder into the page.
3. Netlify will give a public `https://...netlify.app` URL.
4. Use:
   - Privacy Policy URL: `https://...netlify.app/privacy.html`
   - Support URL: `https://...netlify.app/support.html`

## GitHub Pages option

1. Create a public GitHub repository, for example `card-public-pages`.
2. Upload all files from this folder.
3. In the repository settings, open Pages.
4. Set source to the `main` branch and root folder.
5. Use:
   - Privacy Policy URL: `https://USERNAME.github.io/card-public-pages/privacy.html`
   - Support URL: `https://USERNAME.github.io/card-public-pages/support.html`

## Before publishing

Confirm the support email in `privacy.html` and `support.html`:

```text
yumikami.app@gmail.com
```
