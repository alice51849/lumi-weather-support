# Lumi Weather — Support &amp; Privacy site

Static GitHub Pages site for the **Lumi Weather** iOS app (kid-friendly weather companion for parents).
Used for the App Store Connect Support URL, Privacy Policy URL and Marketing URL.

## Files
- `index.html` — landing page (features, privacy promise, links)
- `support.html` — FAQ, how-to, troubleshooting, contact
- `privacy.html` — full privacy policy (matches the app's actual behaviour)
- `styles.css` — shared styling (no frameworks, no trackers)
- `logo.png` / `mascot.png` / `hero.png` — artwork

## Deploy (GitHub Pages)
1. Create a public repo, e.g. `lumi-weather-support`, under your account.
2. Push all files to the default branch (root directory).
3. Repo → Settings → Pages → Source: deploy from branch, root.
4. Wait for the green checkmark; the site goes live at the URL below.

## App Store Connect URLs
- **Support URL:** `https://alice51849.github.io/lumi-weather-support/support.html`
- **Privacy Policy URL:** `https://alice51849.github.io/lumi-weather-support/privacy.html`
- **Marketing URL:** `https://alice51849.github.io/lumi-weather-support/`

(Replace `alice51849` / `lumi-weather-support` if you use a different account or repo name.)

## How to edit
- App name / tagline: edit the `<h1>` and `.tagline` text in each HTML file.
- Contact email: search-replace `hourstag.app@gmail.com`.
- Brand / copyright: search-replace `Cait518` and the year in the footers.
- App Store link: add your App Store URL to the buttons in `index.html` once the app is live.
- If app features change, update `privacy.html` so it always matches real behaviour.

## Notes
- No third-party analytics, ads or external trackers are used.
- The privacy policy reflects a fully on-device app: no account, no data collection, location used only to fetch weather via Apple WeatherKit.
