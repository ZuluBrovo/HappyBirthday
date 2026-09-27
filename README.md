# Zenith OMR Scanner — October 2026

Zenith Aviation Academy · October 2026 New Paper Set · ZAA2020 questions only

Green edition of the OMR scanner. It contains the 10 new Mock 1 papers (AGK to be added later) and the updated student list (71 students, batches 0–8).

---

## How to put it online (GitHub Pages)

### Option A — New repository (recommended)

1. Sign in at **github.com** → click **+** (top right) → **New repository**.
2. Name it `omr-oct2026`, set it to **Public**, and click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Open the unzipped `omr-oct2026` folder, select **all the files inside it** (not the folder itself) and drag them into the browser.
   - `.nojekyll` is a hidden file. If you can't see it, it doesn't matter much, so skip it.
5. Click **Commit changes**.
6. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: main**, **Folder: / (root)** → **Save**.
7. Wait 1–2 minutes and refresh that page. The link appears at the top:
   `https://<your-username>.github.io/omr-oct2026/`

### Option B — Add to the repository you already use for the old scanner

1. Open that repo → **Add file → Upload files**.
2. Drag in the whole **`omr-oct2026` folder** (the folder itself this time) so it lands as a subfolder.
3. **Commit changes**. After a minute it's live at
   `https://<your-username>.github.io/<old-repo-name>/omr-oct2026/`
4. The old scanner stays at its current link, unchanged.

---

## On the phone

- Open the link in **Safari (iPhone)** or **Chrome (Android)**.
- **Add to Home Screen**: iPhone → Share → *Add to Home Screen*; Android → ⋮ → *Install app* / *Add to Home screen*.
- It installs as **"OMR Set 2"** with the dark Zenith icon, separate from the old scanner.
- Allow camera access when asked (Auto-Scan needs it).

## Good to know

- The October scanner keeps its own saved library, so it never mixes papers with the old scanner, even on the same phone.
- Saved data lives in each phone's browser. Use **Library → Export** now and then as a backup.
- To update later (e.g. adding AGK), upload the new `index.html` over the old one (**Add file → Upload files** → Commit). Phones pick up the new papers on the next open. If one doesn't, close and reopen the app.

## Files

| File | What it is |
|---|---|
| `index.html` | The scanner app (papers and student list are built in) |
| `manifest.webmanifest` | Makes it installable ("OMR Set 2", dark Zenith icon) |
| `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` | Android / home-screen icons |
| `apple-touch-icon.png` | iPhone home-screen icon |
| `favicon.png` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |
