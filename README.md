# MMJ First Year Companion

## Open the app

[Launch MMJ First Year Companion](https://mmummj.github.io/MMJCompanion/)

A practical guide and toolkit for first-year Multimedia Journalism students. Use it when you are settling into university, working out what an assessment brief means, responding to feedback, managing deadlines, or deciding who to ask for help.

The companion includes:

- Guidance for starting university and finding your way around course expectations
- Assessment, feedback, deadline, and study-planning tools
- Weekly check-ins to help you pause and review where you are
- A searchable set of common questions and situations
- Private browser-based notes and progress tracking

## Add it to your phone

The app works in a browser, but you can add it to your phone's home screen so it feels more like an app.

### Android

1. Open the [MMJ First Year Companion](https://mmummj.github.io/MMJCompanion/) in Chrome.
2. Open the browser menu using the three dots.
3. Choose **Install app** or **Add to Home screen**.
4. Confirm the installation.

### iPhone or iPad

1. Open the [MMJ First Year Companion](https://mmummj.github.io/MMJCompanion/) in Safari.
2. Tap the **Share** button.
3. Choose **Add to Home Screen**.
4. Tap **Add** to confirm.

The app can cache its main content for offline use. Notes and checklists are stored only in the browser on the device where they were entered.

## For staff and contributors

This is a static Progressive Web App. No build command or package installation is required.

### Publish with GitHub Pages

1. Create a new GitHub repository. A public repository is the simplest option for GitHub Pages.
2. Upload the contents of this folder to the repository's default branch. Keep `index.html` at the repository root.
3. In GitHub, open **Settings -> Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
5. Wait for the deployment to complete. The live app is [https://mmummj.github.io/MMJCompanion/](https://mmummj.github.io/MMJCompanion/).

## Updating the app

After changing `index.html`, commit and push the update. Increment the cache version in `sw.js` (for example, from `mmj-companion-v1` to `mmj-companion-v2`) when you need every returning device to refresh cached app-shell files immediately.

The content is intentionally easy to edit in one HTML file. Programme-specific links, contacts, policies, modules, and assessment dates should be checked before student publication.
