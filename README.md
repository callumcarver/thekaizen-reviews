# thekaizen.co/reviews

Static reviews page served via Cloudflare Worker proxy at https://thekaizen.co/reviews

Hosted on GitHub Pages. Cloudflare in front of thekaizen.co rewrites `/reviews*` to fetch from this repo's GitHub Pages site, so the public URL stays clean and SEO-aligned with the rest of thekaizen.co.

To update: edit index.html, commit, push. Cloudflare cache TTL is 1 hour by default — purge in dashboard for immediate refresh.
