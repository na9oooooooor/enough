# Enough landing page

A lightweight static website built using the actual Enough app icon and App Store screenshots. No dependencies or build step.

## Publish on GitHub Pages

1. On GitHub, create a **new public repository** named `enough` (do **not** use your existing `Activity` repository).
2. Upload **index.html**, **styles.css**, and the whole **assets** folder to the repository root. Commit the files.
3. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch `main`, folder `/(root)`, then **Save**.
5. Your site should appear at `https://na9oooooooor.github.io/enough/` after GitHub finishes deploying it. Check the deployment status in **Actions** or **Pages**.

The files work as static HTML and do not require a domain or paid hosting. Existing App Store and Notion privacy-policy links are included.

## Notes

- The app artwork remains sourced from the provided archive.
- This does not modify the iOS project.
- You can update the copy in `index.html` and colors/layout in `styles.css`.
- For Google indexing, once the site is public, consider verifying it in Google Search Console. Indexing and rankings are not guaranteed.
- The page uses Google-hosted fonts with system-font fallbacks; remove the `@import` in CSS if you prefer no external font requests.
