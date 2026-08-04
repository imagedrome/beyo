# beyo-site

Static site for [beyo.day](https://beyo.day) — landing, Privacy Policy, and Terms of Service.

## Structure

```
index.html
privacy/index.html
terms/index.html
assets/css/style.css
```

HTML + CSS only. System fonts. No frameworks, animations, or dark mode.

## Local preview

```bash
cd /Users/jeanymac/XcodeProjects/beyo-site
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Deploy

Push to the GitHub repo connected to Cloudflare Pages (or your existing host). Root directory = this folder.
