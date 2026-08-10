# paperboat

Marketing site for **Paper Boat Ltd** — fractional CPO, account management and strategic advisory.

Live at [getpaperboat.com](https://getpaperboat.com).

## Stack

Static HTML + CSS. No build step, no dependencies.

```
index.html    # the whole site
styles.css
favicon.svg
```

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Hosted on Vercel. Pushes to `main` deploy automatically.

```bash
vercel --prod
```

## Editing content

All copy lives in `index.html`, in plain sections (`#about`, `#services`, `#how`, `#contact`).
Company details (address, VAT, reg. no.) appear in the contact section and the footer — update both.
