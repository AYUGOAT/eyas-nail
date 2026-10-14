EYA’S NAIL — UPDATED EDITORIAL WEBSITE + INSTALLABLE WEB APP

Includes improved Amharic typography, a working hero-card link, an automatic beauty-photo slideshow, and the installable web app button. The slideshow first tries photos uploaded through the existing admin gallery, then uses fallback beauty photos.

UPLOAD TO THE SAME GITHUB REPOSITORY ROOT (the folder containing your current index.html):
1. Back up your current index.html.
2. Replace index.html with this package’s index.html.
3. Upload/replace manifest.webmanifest and service-worker.js.
4. Upload the entire icons folder.
5. Ensure eyas-nail-logo.png is in the root (upload it if missing).
6. Commit the changes. Do not upload the ZIP itself.

Do not change admin.html or the Render backend. The slideshow reads your existing /api/photos/<service-key> endpoints.

INSTALLATION NOTE: this is a PWA, not an APK download. On supported Android Chrome browsers, the button triggers the native install prompt. If the browser does not offer that prompt (such as some in-app browsers), it shows steps for using the browser menu. On iPhone, open the site in Safari and choose Share → Add to Home Screen.

After publishing, test both languages, Telegram booking, direct booking, service galleries, slideshow, and installation.
