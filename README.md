
# Zairyan Lab – Mini Site

This repository contains a small multi-page static site for testing analytics (GTM/GA4), forms, navigation, and downloads without touching production systems.

## Pages
- `index.html` – home with newsletter mock + CTA.
- `about.html` – what this lab is + banner placeholder.
- `tools.html` – working budget calculator (JS) with `dataLayer` events.
- `articles.html` – sample articles to simulate content.
- `contact.html` – Monday.com embedded form + click-to-call/email.
- `robots.txt` – blocks indexing during tests.
- `styles.css` – shared look & feel.

## Assets
- `/assets/test-guide.pdf` – placeholder PDF for download tracking.
- `/assets/logo-placeholder.png` – sample logo.
- `/assets/banner-placeholder.jpg` – sample banner graphic.
- `/assets/sample-data.json` – for future JS fetch experiments.

## GTM
Search for the comments "GTM HEAD SNIPPET PLACEHOLDER" and "GTM BODY SNIPPET PLACEHOLDER" and paste your Tag Manager snippets there when ready.

## Notes
- Keep `robots.txt` and the `<meta name="robots" ...>` tag until you want the lab indexed.
- For the contact form, the Monday.com link is embedded via an iframe (`https://wkf.ms/42E4faw`). Update if you regenerate the form.
