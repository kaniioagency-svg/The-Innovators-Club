# The Innovators Club™

Website for The Innovators Club™, a private community for young visionaries, entrepreneurs, creators, investors and leaders.

Single-file static site: `index.html` (HTML, CSS and JS inline; GSAP loaded from cdnjs, fonts from Google Fonts).

## Run locally
Open `index.html` in a browser.

## Deploy with GitHub Pages
1. Push this repo to GitHub.
2. Settings > Pages > Deploy from branch > `main` / root.
3. Custom domain: `theinnovatorsclub.online` (the `CNAME` file already sets it).
4. In GoDaddy DNS, add four `A` records on `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a `CNAME` for `www` pointing to `<your-username>.github.io`.
5. Enable "Enforce HTTPS" once the certificate is ready.

## To do
- Replace placeholder logo mark with the official logo.
- Replace sample testimonials and stats with real ones.
- Connect the application form and newsletter to a backend (Formspree, Netlify Forms, etc.).
