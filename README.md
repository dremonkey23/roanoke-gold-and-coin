# Roanoke Gold & Coin Homepage Mockup

Static one-page homepage concept for **Precious Metal and Coins** in Roanoke, VA.

## Goal
Create a cleaner, more modern homepage focused on:
- gold
- silver
- platinum
- coins
- appraisals
- local trust
- review-driven credibility

And remove the old broad-positioning feel around jewelry, watches, diamonds, and miscellaneous retail inventory.

## Files
- `index.html` — the full one-page mockup
- `assets/hero.jpg` — current-site store image used in the hero
- `assets/gold.jpg` — current-site gold image
- `assets/silver.jpg` — current-site silver image
- `assets/coins.jpg` — current-site coin image

## Content inputs used
- Current website: `https://www.roanokegoldandcoin.com/`
- Verified Google Maps rating visible in browser: `4.9`
- Existing review quote currently shown on the live site
- Current phone and email from the live site / Google Maps listing

## Notes before final launch
1. Confirm the final brand name to show in the header:
   - `Precious Metal and Coins`
   - or `Roanoke Gold & Coin`
2. Confirm whether the business still buys scrap precious-metal jewelry for melt value.
3. Replace the temporary contact/location note with:
   - final address
   - hours
   - map embed if wanted
4. Pull in 3–5 real Google review excerpts that support:
   - fair pricing
   - honest appraisals
   - expertise
   - no-pressure experience

## View locally
From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```

## GitHub Pages-ready
This is plain static HTML, so it can be published quickly with:
- GitHub Pages
- Netlify
- Vercel
- any simple static host

No framework or build step required.

A GitHub Actions Pages workflow is included at:
- `.github/workflows/deploy-pages.yml`

Once this repo is pushed to GitHub and Pages is set to **GitHub Actions**, each push to `main` will redeploy the site automatically.
