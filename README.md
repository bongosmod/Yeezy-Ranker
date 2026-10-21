# Yeezy Ranker

A fan-made Kanye West song ranking website starter, designed for GitHub Pages.

## Features
- Browse albums and track listings.
- Rate songs from 1–10.
- Build a personal Top 10 with ten unique tracks.
- Create a demo profile and browse other profiles/lists in the same browser.
- Listen to available 30-second song previews when iTunes/Apple's search API has one; otherwise use Spotify or YouTube Music search links.
- Responsive dark theme with neon-lime accents.

## Publish on GitHub Pages
1. Download and unzip `yeezy-ranker.zip`.
2. Create a GitHub repository named `yeezy-ranker` (or use an existing repository).
3. Upload **the contents of this folder** to the repository root. `index.html`, `app.js`, `albums.json`, and `style.css` should sit at the top level.
4. In GitHub, open **Settings → Pages**.
5. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for the Pages deployment to finish.

## Important limitations
This is a static prototype. Demo accounts, passwords, ratings, and lists are stored in the current browser's `localStorage`; they are not secure and do not sync across devices or appear to other visitors. For real public accounts and shared community rankings, connect a backend such as Supabase or Firebase, add proper authentication, and store ratings/lists in a database. Do not use a real/reused password here.

The song catalogue is a starter track list, not a verified authoritative discography; album editions and track lists can vary. The 2026 BULLY entry is marked as subject to change. The preview player relies on third-party availability and only plays preview clips, not full songs. Full playback depends on licensing and supported streaming services.

## Customization
- Edit `albums.json` to change albums and tracks.
- Edit `style.css` to change the visual design.
- Main interaction logic is in `app.js`.
