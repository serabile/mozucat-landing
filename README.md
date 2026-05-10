# Landing — mozucat.com

Static single-page landing for Mozucat (IPTV client)

## Local preview

```bash
cd landing && python3 -m http.server 8080
# open http://localhost:8080
```

## Structure

```
landing/
  index.html          # single-page site (HTML + inline CSS + minimal JS)
  assets/
    mozucat-cat.png   # mascot / favicon / og:image
    mozucat-logo.png  # horizontal wordmark
  screenshots/
    01-home-iphone.png
    02-live-iphone.png
    03-films-iphone.png
    04-series-iphone.png
    05-player-iphone.png
```

## TODOs before going live

- Replace `href="#"` on the App Store / Google Play badges with real store URLs (search for `TODO:` in `index.html`).
- Hook up the legal pages (mentions legales, confidentialite, CGU).
- Verify `ads@mozucat.com`, `contact@mozucat.com`, `support@mozucat.com` mailboxes exist.
