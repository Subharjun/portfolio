# Subharjun Bose — Portfolio

Static, scroll-driven portfolio site. No build step — plain `index.html` + assets.

## Deploy on Render (static site)

This repo includes a `render.yaml` blueprint.

**Option A — Blueprint (uses render.yaml):**
1. Render Dashboard → **New** → **Blueprint**.
2. Connect this GitHub repo. Render reads `render.yaml` and configures a static site.
3. **Apply** → wait for the deploy → you get a `*.onrender.com` URL.

**Option B — Manual static site:**
1. Render Dashboard → **New** → **Static Site**.
2. Connect this repo. Settings:
   - **Build Command:** *(leave empty)*
   - **Publish Directory:** `.`
3. **Create Static Site.**

Every push to the default branch auto-deploys.

## AdSense

`index.html` loads the Google AdSense script (`pub-4720829854209116`). After the site is
live on Render, add the Render URL (or a custom domain) in
[adsense.google.com](https://adsense.google.com) and submit for review. A commented-out
ad-unit template sits in the contact section — uncomment and add a real `data-ad-slot`
once approved.
