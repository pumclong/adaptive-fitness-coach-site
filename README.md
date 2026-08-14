# Adaptive Fitness Coach public site

This directory is the standalone public website for Adaptive Fitness Coach. It contains the App Store privacy-policy and support URLs without publishing the application source code.

Expected GitHub Pages address:

`https://pumclong.github.io/adaptive-fitness-coach-site/`

Public pages:

- Overview: `https://pumclong.github.io/adaptive-fitness-coach-site/`
- Privacy: `https://pumclong.github.io/adaptive-fitness-coach-site/privacy.html`
- Support: `https://pumclong.github.io/adaptive-fitness-coach-site/support.html`
- Support issues: `https://github.com/pumclong/adaptive-fitness-coach-site/issues`

## Publishing boundary

Only the contents of this directory should be copied into the public `pumclong/adaptive-fitness-coach-site` repository. Do not publish the parent fitness workspace, mobile source, signing material, build artifacts, exports, screenshots containing user data, or private fitness records.

The site is deliberately dependency-free:

- Static HTML and CSS only
- No analytics, advertising, tracking pixels, scripts, external fonts, or asset CDN
- Relative internal links suitable for a GitHub project page
- `.nojekyll` included for direct static serving

## GitHub Pages setup

After creating the public repository and pushing these files to its default branch:

1. Open the repository’s **Settings → Pages**.
2. Choose **Deploy from a branch**.
3. Select the default branch and the repository root (`/`).
4. Save and wait for the Pages deployment to finish.
5. Verify the overview, privacy, support, issue, and 404 links.

Do not add an App Store download badge or availability claim until the app has passed review and its distribution link is active.

## Content maintenance

- Privacy-policy effective date: 15 August 2026
- Recheck the policy whenever data storage, account, analytics, sensors, cloud services, media hosting, or distribution changes.
- Replace the release-preparation wording only after release is confirmed.
- Keep exercise/progression professional-review language until that review is complete.
