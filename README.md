# EVGO corporate website (www.evgo.earth)

Static site: plain HTML and CSS, no build step. Open `index.html` in a browser to preview,
or serve the folder locally with `python3 -m http.server` from this directory.

- `index.html`: all sections (About and vision, Mobility, Charging infrastructure, Our chargers, Contact)
- `styles.css`: responsive layout for phones, tablets, laptops and desktops
- `assets/`: logo, favicon and optimized photos

## Hosting

Any static host works (Netlify, Vercel, Cloudflare Pages, GitHub Pages). Publish this folder
(`apps/site`) as the site root.

The domain's DNS is at GoDaddy and GoDaddy email is in use. When pointing the domain at the
host, change only the website records (the `@` A record and the `www` CNAME). Do not change
the MX, SPF/TXT or other email records.
