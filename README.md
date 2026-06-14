# Mohawk Valley Somali Bantu Community Association

Official website for the **Mohawk Valley Somali Bantu Community Association, Inc.** — a 501(c)(3) nonprofit in Utica, NY supporting Somali Bantu refugees and immigrant families with resettlement, interpretation, education, youth, and self-sufficiency services.

🌐 https://mvsbca.org · EIN 27-0158992

## Structure
Static HTML site — no build step required.

```
index.html  about.html  services.html  leadership.html  contact.html  donate.html
assets/css/styles.css   assets/js/main.js   assets/favicon.svg
```

## Run locally
```
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy
Served via GitHub Pages from the `main` branch (custom domain set in `CNAME`).

## To finalize (confirm with org)
- Leadership names/titles/photos (currently: Abdullahi Najeni + placeholders)
- Exact services offered + any program stats
- Contact form endpoint (Formspree) and online donation link
- Set up email `info@mvsbca.org` (MX) before applying to Claude for Nonprofits
