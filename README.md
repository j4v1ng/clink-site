# clink.geyser-iis.com

The website for Clink, the bill-splitting app by Geyser Intelligent Information Systems LLC: a home page and the privacy policy that Google Play links to (`/privacy/`). Plain HTML and CSS, served by GitHub Pages from `main`; `CNAME` holds the domain.

The privacy policy here must match `store/privacy-policy.md` and the Data safety answers in the app's repo.

Font: Archivo (SIL Open Font License, `fonts/OFL.txt`).

The home page links to Google Play (`com.geyseriis.clink`), with a QR code for computer screens (`play-qr.svg`, made with Python's `qrcode`). Search engines get a canonical address, a share image (`og-image.png`, the Play feature graphic), app details in JSON-LD, `robots.txt` and `sitemap.xml`. Update `sitemap.xml`'s dates when a page changes.
