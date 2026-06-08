# Skinfile Static Site

Deploy the contents of this `landing/` directory as the document root for `https://skinfile.app`.

Full deployment steps are in `docs/landing_deploy.md`.

Required public URLs for App Store Connect:

- `https://skinfile.app/`
- `https://skinfile.app/privacy/`
- `https://skinfile.app/support/`
- `https://skinfile.app/terms/`
- `https://skinfile.app/medical-disclaimer/`
- `https://skinfile.app/sitemap.xml`
- `https://skinfile.app/robots.txt`

Before submission, verify:

```bash
node scripts/check_landing_links.js
bash scripts/skinfile_external_launch_check.sh
```

The legacy `.html` legal pages are kept for compatibility, but canonical and internal links point to the clean directory URLs.
