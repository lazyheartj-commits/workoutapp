# Iron Week Log

A weightlifting log for planning your own week. Every day starts blank. You add exercises from a list of about 85, grouped by muscle, or type in your own, then log weight and reps for each set. The week strip at the top shows which muscle groups each day covers. The app can be installed on your phone's home screen and works offline once it has loaded.

## Put it on GitHub Pages (free)

1. Sign in at github.com and click **New repository**. Name it something like `iron-week`, make it **Public**, and click **Create repository**.
2. On the new repo page, click **uploading an existing file**. Drag in every file from this folder (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`), then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then click **Save**.
4. Wait a minute or two, then refresh the page. Your app link appears at the top, for example `https://YOUR-USERNAME.github.io/iron-week/`.

## Install it on your phone

- **iPhone (Safari):** open the link, tap Share, then tap **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the ⋮ menu, then tap **Install app** or **Add to Home screen**.

## Using it

- Tap a day at the top, then use **Add an exercise** to choose a muscle group and an exercise. To add something that isn't listed, pick **Custom exercise…** at the bottom of the exercise list.
- You can name each day, for example "Push" or "Rest".
- Use **+ Set**, **− Set**, **↑** and **↓** to adjust your sets and the exercise order.
- Check off sets as you finish them, then tap **Finish workout**. Your best set is saved as "Last time" for next week.

## Notes

- Your logs are saved on the device and browser you use. They don't sync between devices.
- To add more choices to the exercise list, edit `LIB` in `index.html`. Each entry is `["Name", default sets, "default reps"]`. Cardio & Mobility entries are `["Name", default minutes]`.
- If an update doesn't show up after you upload new files, change `CACHE` in `sw.js` to a new name, such as `iron-week-v7`.
