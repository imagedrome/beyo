# beyo-site

Static site for [beyo.day](https://beyo.day) — poster landing, Privacy Policy, and Terms of Service.

## Structure

```
index.html                 # Poster landing (assets under assets/images/)
privacy/index.html
terms/index.html
assets/css/style.css
assets/images/
```

HTML + CSS only. No frameworks or build step (landing uses a small mailto script).

SEO: `title` / `description` / canonical, Open Graph + Twitter Card, `SoftwareApplication` JSON-LD, `robots.txt`, `sitemap.xml`, favicon / apple-touch-icon, `og-share.png` (1200×630), and visually-hidden semantic copy (no keyword stuffing).

## Local preview

```bash
cd /Users/jeanymac/XcodeProjects/beyo-site-github
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Deploy

Push to the GitHub repo connected to Cloudflare Pages. Root directory = this folder.
Build command: none. Output directory: `/` (project root).
