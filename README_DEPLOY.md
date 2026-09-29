# Jayaditya Portfolio — deployment package

## Files
- `index.html` — complete portfolio page
- `assets/profile.png` — supplied illustrated portrait

## Important security change
The original HTML contained a Gemini API key directly in browser JavaScript. That key has been removed from this deployment version. A public website must not contain a private API key. The AI Synergy Engine is now a local client-side simulation, so this version works on static hosting without exposing credentials.

If the original key was real, revoke/rotate it in the provider dashboard before publishing.

## Quick local preview
Open `index.html` in a browser. For the most reliable local preview, use a simple local server such as VS Code Live Server.

## GitHub Pages deployment
1. Create a GitHub repository, e.g. `jayaditya-portfolio`.
2. Upload `index.html` and the entire `assets` folder.
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the branch containing `index.html` (usually `main`) and folder `/ (root)`.
6. Save and wait for GitHub Pages to publish the site.
7. GitHub will show the public site URL.

## Netlify deployment
Drag the whole `jayaditya-portfolio` folder into Netlify's manual deploy area, or connect the GitHub repository.

## Before publishing
Check the public page for any personal details or links that should not be public. Anything included in the deployed HTML or assets should be treated as public.