# Select Streak: install on your iPhone (no Mac needed)

Select Streak installs as a Home Screen app. It gets Byte's icon, opens full screen with no Safari bars, and works offline. It's free and takes about 10 minutes.

## Step 1: Put the app online with GitHub Pages (free)

Do this on your laptop.

1. Make a free account at https://github.com, or sign in.
2. Click **+** (top right) → **New repository**. Name it `select-streak`, set it to **Public**, and click **Create repository**.
3. On the next page, click **uploading an existing file**.
4. Unzip this folder. Select **everything inside it** (the `fonts` and `icons` folders, `index.html`, `manifest.webmanifest`, `sql-asm.js`, `sw.js`) and drag it all into the upload box. Click **Commit changes**.
   - Upload the files *inside* the folder, not the folder itself, so `index.html` ends up at the top level.
5. Go to **Settings** → **Pages** (left menu). Under **Branch**, pick **main** and **/ (root)**, then click **Save**.
6. Wait 1–2 minutes and refresh. GitHub shows your link: `https://YOUR-USERNAME.github.io/select-streak/`

## Step 2: Install it on your iPhone

1. Open the link in **Safari**. It has to be Safari, not Chrome.
2. Tap the **Share** button (the square with the arrow), then **Add to Home Screen**.
3. Make sure **Open as Web App** is on, then tap **Add**.

Byte now sits on your Home Screen. Open the app once while you're online; after that it works without internet.

## Good to know

- **Sound:** sounds play through the ringer, so flip the silent switch off to hear the dings.
- **Haptics:** on iOS 18 and newer you'll feel light taps on answers. Older iOS has no web haptics. Turn haptics or sound off in **Profile → Settings**.
- **Progress** is saved on your phone. Deleting the app from your Home Screen erases it.
- **Updating the app:** upload the changed files to the same GitHub repository. Also open `sw.js` and change `select-streak-v2` to `select-streak-v3` (then v4, and so on). Otherwise phones keep the old cached copy. Close and reopen the app twice to pick up the update.
- **Who can see it:** anyone who has the link can open it, but nobody will find it unless you share it.
