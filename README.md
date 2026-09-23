# Tiffin Tracker

A single-page app to track your 60-meal tiffin cycle (lunch + dinner). Data is saved in your browser's `localStorage`, so it stays on whichever device/browser you use it on.

## Run it locally
Just double-click `index.html` — it opens in your browser, no server needed.

## Put it on GitHub + host it free (GitHub Pages)

1. **Create a repo**
   - Go to https://github.com/new
   - Name it something like `tiffin-tracker` → Create repository (keep it empty, no README).

2. **Upload the files**
   - On the new repo page, click **"uploading an existing file"**.
   - Drag in `index.html` and `README.md` from this folder.
   - Scroll down, click **Commit changes**.

3. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages** (left sidebar).
   - Under "Build and deployment" → Source, choose **Deploy from a branch**.
   - Branch: `main`, folder: `/ (root)` → **Save**.

4. **Open your live site**
   - Wait ~1 minute, then refresh the Pages settings page — it'll show a link like:
     `https://<your-username>.github.io/tiffin-tracker/`
   - That's your personal tracker, live and free, forever.

5. **Update it later**
   - Edit `index.html` in the repo (pencil icon) or upload a new version → commit.
   - Pages rebuilds automatically in under a minute.

## Note on data
By default data is saved in `localStorage`. To save it online (free) with Supabase, paste `SUPABASE_URL` and `SUPABASE_KEY` inside `index.html`. Then the app asks for your email (magic link) and syncs your data across phone and laptop.
