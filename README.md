# MemVLN Project Page

Static project page for **MemVLN: Streaming Episodic Memory for Vision-Language Navigation**.

## Local Preview

```bash
python3 -m http.server 8026 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8026/>.

## Deployment

The public project page is hosted at <https://memvln.github.io/> using GitHub
Pages. The workflow in `.github/workflows/pages.yml` deploys the static files
without a build step.

After pushing an update to `main`, deploy it from the workflow's **Run workflow**
button, or run:

```bash
gh workflow run pages.yml --repo MemVLN/MemVLN.github.io --ref main
```
