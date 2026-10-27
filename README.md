# MemVLN Project Page

Static project page for **MemVLN: Streaming Episodic Memory for Vision-Language Navigation**.

[Project page](https://memvln.github.io/) · [Paper: arXiv:2610.35066](https://arxiv.org/abs/2610.35066)

## Local Preview

```bash
python3 -m http.server 8026 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8026/>.

## Paper Figures

The teaser and method images are rendered directly from the original figure PDFs
in the [arXiv:2610.35066v1 LaTeX source archive](https://arxiv.org/src/2610.35066v1):

| Website image | Source figure |
| --- | --- |
| `assets/images/teaser.png` | `figures/VLN_teaser.pdf` |
| `assets/images/method.png` | `figures/VLN_model.pdf` |

Both PNGs use the PDF crop box and a width of 3200 pixels. The image URLs in
`index.html` include a content hash to refresh cached copies after an update.

## Deployment

The public project page is hosted at <https://memvln.github.io/> using GitHub
Pages. The workflow in `.github/workflows/pages.yml` deploys the static files
without a build step.

After pushing an update to `main`, deploy it from the workflow's **Run workflow**
button, or run:

```bash
gh workflow run pages.yml --repo MemVLN/MemVLN.github.io --ref main
```
