# MMJ First Year Companion

A static Progressive Web App for first-year Multimedia Journalism students.

## Publish with GitHub Pages

1. Create a new GitHub repository. A public repository is the simplest option for GitHub Pages.
2. Upload the contents of this folder to the repository's default branch. Keep `index.html` at the repository root.
3. In GitHub, open **Settings -> Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
5. Wait for the deployment to complete. GitHub will provide the site URL, usually `https://USERNAME.github.io/REPOSITORY/`.

No build command or package installation is required.

## Install on phones

- **Android:** Open the Pages URL in Chrome, then choose **Install app** or **Add to Home screen** from the browser menu.
- **iPhone/iPad:** Open the Pages URL in Safari, tap **Share**, choose **Add to Home Screen**, then confirm.

The site must be served over the GitHub Pages HTTPS URL for installation and offline caching to work. The service worker caches the app shell and the app's existing student notes remain local to each device/browser.

## Updating the app

After changing `index.html`, commit and push the update. Increment the cache version in `sw.js` (for example, from `mmj-companion-v1` to `mmj-companion-v2`) when you need every returning device to refresh cached app-shell files immediately.

The content is still intentionally easy to edit in one HTML file. Programme-specific links, contacts, policies, modules, and assessment dates should be checked before student publication.
