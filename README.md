# SFHS Football Pool dashboard

A free, public, static website for GitHub Pages. No paid hosting, database, API key, or build process required.

## Publish

1. On GitHub, create a **public** repository named `sfhs-football-pool`.
2. Upload **index.html**, **styles.css**, **app.js**, and **data.json** from this folder to the repository root (Add file → Upload files → Commit changes).
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
4. After deployment, visit `https://YOUR-USERNAME.github.io/sfhs-football-pool/`.

## Updating the site

- Open the public site, make edits under Weekly picks / Future schedule / Market analytics.
- Click **Export data**. This downloads an updated `data.json`.
- On GitHub, open the repository's `data.json`, choose **Edit** (pencil), replace the contents with the exported file's contents, and commit. Alternatively use **Add file → Upload files** and replace `data.json`.
- Refresh the site after GitHub Pages deploys. **Browser edits alone do not update the public site.** Export frequently; edits are not saved automatically.
- The Import data button loads an exported JSON into the browser for further edits.

## Limitations

- **No automatic odds, injury, score, or NFL future-schedule feed.** Those require an external provider/integration. Future NFL matchups must be entered/imported as they become available. Week 7 matchups are seeded.
- Historical Weeks 4–5 are explicitly unknown. Weeks 1–3 and 6 are reported aggregate win-loss records; they do not establish weighted points.
- The pool organizer determines which NFL games receive 2 points. Enter the official weights manually; the app validates 20 total points before locking a week.
- There is no sign-in or private data. Public site visitors can edit their own browser session but cannot publish changes without GitHub repository permissions.
- A static public site is not a secure shared-editing database. Keep exported backups and avoid including personal information.
