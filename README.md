# our-little-home-cdn

Static assets for the *Our Little Home* app (storybooks and theme-park models), served over
GitHub Pages so the Android app can stay small. The app fetches `assets/books/*` and
`assets/park/*` from here on first use and caches them on the device.

Layout must mirror the app's `public/` folder: `assets/books/…`, `assets/park/…`.

Publish: push to `main`, then Settings → Pages → Deploy from branch → `main` / root.
Files are identical to the ones in the app repo; keep the two in sync when art changes.
Licences of the bundled third-party art are listed in the app's Credits screen.
