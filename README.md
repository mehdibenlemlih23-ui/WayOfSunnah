# WayOfSunnah

A premium storefront for digital products (planners, workbooks, trackers, adhkar cards and a kids pack) that help the ummah live the Sunnah of the Prophet Muhammad ﷺ.

Single-file static site: no build step, ready for **GitHub Pages**.

## Publish on GitHub Pages
1. Create a new repository on GitHub named `WayOfSunnah` (public).
2. Upload `index.html` and `README.md` (Add file → Upload files → Commit).
3. Go to **Settings → Pages**, set Source to `Deploy from a branch`, branch `main`, folder `/ (root)`, then Save.
4. After a minute your site is live at `https://<your-username>.github.io/WayOfSunnah/`.

## Connect payments
Open `index.html`, find `EDIT YOUR PRODUCTS HERE` near the bottom, and paste your checkout links (Gumroad, Payhip, Lemon Squeezy, etc.) into each `buyUrl` and into `BUNDLE_URL`. Until a link is added, the Buy button shows a "launching soon" message.

You can also edit titles, prices, descriptions and colours in the same `PRODUCTS` list.
