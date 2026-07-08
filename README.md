# Deen Kids TV — Android App (APK) Build Kit 📱🌙

This folder turns your app into a real installable Android app — **no coding and no software to install on your computer**. GitHub's servers do the building for you.

## Step 1 — Create the repository
1. Go to **github.com/new**
2. Repository name: `deen-kids-tv-app`
3. Private is fine. Click **Create repository**.

## Step 2 — Upload these files
1. On the new repo page, click the **"uploading an existing file"** link.
2. Drag **everything inside this unzipped folder** into the upload box — the `www` folder, `assets` folder, `package.json`, `capacitor.config.json`, and the `.github` folder.
3. Click **Commit changes**.

> ⚠️ **If you don't see a `.github` folder when dragging** (it's hidden on Mac):
> In the repo click **Add file → Create new file**, name it exactly
> `.github/workflows/build-apk.yml`
> and paste the contents of the `build-apk.yml` you'll find in this kit (open it with any text editor), then **Commit**.

## Step 3 — Let GitHub build it
1. Click the **Actions** tab of your repo.
2. You'll see **"Build Android APK"** running — it takes about 10–15 minutes.
3. If it isn't running, open it and press **Run workflow**.

## Step 4 — Download your app
- Easiest: repo front page → **Releases** (right sidebar) → **Deen Kids TV — Android App** → download **app-debug.apk**
- Or: Actions → the green run → **Artifacts** → `Deen-Kids-TV-APK`

## Step 5 — Install on the phone
1. Get `app-debug.apk` onto the Android phone (download it there directly, or WhatsApp it to yourself).
2. Tap the file → Android asks to allow installs from this source → **Allow** → **Install**.
3. Done! Deen Kids TV appears in the app drawer with its own icon — fullscreen, works offline, progress saves on the phone.

## Updating the app later
Replace `www/index.html` with a newer version (repo → `www` folder → **Add file → Upload files**) — a fresh APK builds automatically within minutes.

## Notes
- Games, books and learning all work **offline**; the video clips and YouTube player need internet.
- Sharing with family: send them the APK file directly (WhatsApp/Drive) — they install the same way.
- This APK is **not** on the Play Store. If you ever want that: a Google Play developer account ($25, one time) + upload a signed build — say the word and the kit can be extended for it.
