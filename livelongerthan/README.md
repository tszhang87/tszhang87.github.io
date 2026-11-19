# LiveLongerThan 🌱

A bilingual, privacy-friendly site celebrating the time you have lived and the small milestones ahead.

Inspired by Shu Liu (刘舒), with love.

## Links

- GitHub Pages project URL: https://tszhang87.github.io/livelongerthan/
- Source: https://github.com/tszhang87/tszhang87.github.io/tree/main/livelongerthan

## Local use

Open `index.html` in a regular browser or serve it with `python3 -m http.server 8000`.

Birthday calculations happen locally in the visitor's browser; the birthdate is not uploaded, stored, or included in URL parameters. Animal lifespans are illustrative, and the site does not predict lifespan.

## Custom domain: Cloudflare Pages (recommended)

Do **not** configure the custom domain directly on the `tszhang87.github.io` repo's GitHub Pages settings because that could change the existing personal website's main domain.

1. Register `livelongerthan.com` only if available at a registrar; verify the first-year, renewal, and any premium pricing at checkout.
2. In Cloudflare dashboard select **Workers & Pages → Create → Pages → Connect to Git** and authorize this repository.
3. Configure production branch `main`, root directory `livelongerthan`, framework preset **None**, no build command, output directory `.`.
4. Deploy. Under **Custom domains**, connect `livelongerthan.com` and optionally `www.livelongerthan.com`. Follow the generated DNS instructions and enable HTTPS.
5. Enable **Web Analytics** in Cloudflare Pages project settings. This yields visits, page views, referrers, countries, and trends without storing visitors' entered birthdays. Verify analytics beacon or injection after deployment.

## Validation

Check date submission, future-date error, Chinese/English switch, filter categories, next milestone, source links and mobile layout.

No third-party libraries or server dependencies.
