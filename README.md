# DAY//2004

Ready-to-deploy project. No coding needed — just upload, GitHub builds it automatically.

## 1. Upload to GitHub (no git commands needed)

1. Go to https://github.com and log in to your existing account.
2. Click the **+** icon (top right) → **New repository**.
3. Name it `day2004-app`, keep it Public, click **Create repository**.
4. On the new repo page, click **"uploading an existing file"**.
5. Drag this entire folder's contents into the upload box — including the hidden `.github` folder (make sure your file manager shows hidden files, or unzip with a tool that keeps it) and the `src` folder.
6. Scroll down, click **Commit changes**.

## 2. Turn on GitHub Pages (one-time setup)

1. In your new repo, go to **Settings → Pages** (left sidebar).
2. Under **"Build and deployment" → Source**, choose **"GitHub Actions"**.
3. That's it — no need to pick a branch or folder.

## 3. Let it build

1. Go to the **Actions** tab of your repo.
2. You'll see a workflow run start automatically (triggered by your upload). Wait ~1-2 minutes for it to finish (green checkmark).
3. Go back to **Settings → Pages** — your live link will be shown at the top, looking like:
   `https://YOUR-USERNAME.github.io/day2004-app/`

Every time you upload new changes to this repo, it rebuilds and updates automatically.

## Add to your phone's home screen

1. Open your `github.io` link in **Safari** (iPhone) or **Chrome** (Android).
2. Tap the Share button.
3. Tap **"Add to Home Screen"**.
4. It'll appear as an app icon and open full-screen, no browser bar.
