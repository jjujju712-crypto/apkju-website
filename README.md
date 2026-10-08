# apkju

A responsive, English, single-page company website for apkju, focused on AI education and AI products.

- Contact: 010-7763-1234 / +82 10-7763-1234
- Intended custom domain: apkju.com
- Static HTML and CSS; no installation or build step required.

## GitHub Pages

Publish the `main` branch from `/ (root)` in Settings → Pages.

For the custom domain, save `apkju.com` in Settings → Pages → Custom domain after preparing the DNS records below. GitHub creates the `CNAME` file when this setting is saved. Enable Enforce HTTPS when the certificate is ready.

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | jjujju712-crypto.github.io |

Use the hostname only, without `https://` or a repository path. A TTL of 3600 seconds or the provider's default is suitable. Replace conflicting records for `@` and `www`; keep mail-related MX and TXT records.

DNS changes may take up to 24 hours to propagate. Custom-domain HTTPS can take time after DNS propagation.

Reference: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

