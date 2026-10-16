# Little Nap Planner

A tiny installable web app for iPhone and Android. No backend, no logins, no shared data.

## Deploy on GitHub Pages

1. Sign in to GitHub, click **New repository**, name it `little-nap-planner`, select **Public**, and create it.
2. In the new repository, choose **Add file > Upload files**.
3. **Unzip the download** and upload the contents of this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, and the `icons` folder). Do not upload only the ZIP.
4. Commit the files to the `main` branch.
5. Choose **Settings > Pages > Build and deployment > Source: Deploy from a branch**, select `main` and `/(root)`, then **Save**.
6. Open `https://YOUR-USERNAME.github.io/little-nap-planner/` once the Pages deployment completes.

## Install

- **iPhone:** Open that link in Safari > Share > Add to Home Screen > enable Open as Web App (if shown) > Add.
- **Android:** Open in Chrome > menu > Install app (or Add to Home screen).

## Notes

- Times and settings are stored **locally on each device** in the browser. Clearing site data or uninstalling may remove them.
- Works offline after the first successful visit while online and caching completes.
- GitHub Pages is public, so **do not upload private baby information** to the repository. The schedule data stays on the phone.
- For updates, replace `index.html` and increment `CACHE_NAME` in `sw.js` before uploading. Previously installed copies may need to reopen online or have site data refreshed.
- The planner is a scheduling aid, not medical advice.
