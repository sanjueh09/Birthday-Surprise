# For Anu ♡ — birthday website

A mobile-first static birthday website made with HTML, CSS and JavaScript. The photos supplied in the conversation are included in `assets/`.

## Preview locally
Open `index.html` in a browser. For a more reliable local preview, run a static server from this folder, for example `python -m http.server 8000`, then visit `http://localhost:8000`.

## Publish free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a new public repository (for example `for-anu`).
3. Upload `index.html`, `README.md`, and the entire `assets` folder. Keep the folder structure unchanged.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish and open the URL it provides. Test it on a phone.
7. Generate a QR code using the exact published URL. Test the printed code before giving it to Anu.

## Notes
- The opening page currently shows the favourite couple photo supplied first.
- The music button opens the YouTube Music URL provided by the user; it does not stream audio inside the website.
- The Lumbini answer gate is only a playful prompt, not real security. Anyone can inspect a static website's code or guess the answer. Avoid posting the public URL if you want the surprise to stay less discoverable.
- Review all photos and text before publishing. GitHub Pages sites are public to anyone who has the URL.
