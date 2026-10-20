# Azzeddine Talha — Portfolio Website

A clean, responsive, single-page portfolio built with plain HTML, CSS, and a small amount of JavaScript. It has no build step or external library dependencies.

## Files

- `index.html` — the main landing page.
- `privacy-policy.html` — privacy-policy page for Android games using AdMob/AppLovin.
- `assets/files/Azzeddine_Talha_CV.pdf` — CV download.
- `assets/files/Azzeddine_Talha_Portfolio.pdf` — portfolio PDF.
- `assets/images/` — your profile photo, game thumbnails cropped from the supplied portfolio PDF, and logo-based favicon/site icon (generated from the supplied AT logo).

## Preview locally

Open `index.html` in a browser. For a local web server, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish to `azzeddine-talha.me`

Upload the contents of this folder to the public root of your website hosting. Keep the relative folder structure intact so the images, PDFs, and privacy policy load correctly. The homepage will be `https://azzeddine-talha.me/` and the policy URL will be `https://azzeddine-talha.me/privacy-policy.html` if your domain's document root points to this folder.

## Before publishing

1. `assets/images/azzeddine-talha.jpg` is your portrait used in the hero section.
2. The GitHub icon currently points to `https://github.com/` because an exact profile URL was not available in the reference material. Replace that URL in the navigation and footer with your own profile.
3. Review all store destinations and project descriptions before publishing. The selected games currently use the Steam and Google Play pages found for those titles.
4. If any professional links or project information changes, update the corresponding anchors and text in `index.html`.
5. The homepage shows an animated violet-blue loading screen before revealing the content, plus subtle hero and scroll-entrance animations. The animations respect reduced-motion preferences.

## Editing social links

The social links appear twice in `index.html` (header and footer). Search for `TalhaAzzeddine`, `azzeddine-talha-796a98254`, `github.com/`, `play.google.com/store/search`, and `store.steampowered.com/app/3005210` to update them.

## Branding

The site and privacy policy use a deep navy-purple background with electric violet and blue accents inspired by the supplied AT logo. The browser favicon and Apple touch icon are built from that logo. The header displays only the name Azzeddine Talha.
