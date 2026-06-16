# MemVLN Project Page

Static project page for **MemVLN: Streaming Episodic Memory for Vision-Language Navigation**.

## Local Preview

```bash
python3 -m http.server 8026 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8026/>.

## Deployment

This repository is ready for GitHub Pages deployment via the included workflow in
`.github/workflows/pages.yml`.

Because this repository is currently private, GitHub Pages may require either an
upgraded GitHub plan or making the repository public before the workflow can
deploy. While keeping the repository private, the same static files can also be
deployed through Vercel, Netlify, or Cloudflare Pages with no build step.
