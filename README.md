# Open NeuroAI Lab

Hugo + PaperMod site for a personal NeuroAI research website.

## Local Preview

Install Hugo Extended `0.146.0` or newer, then run:

```bash
hugo server -D
```

Open the local URL printed by Hugo, usually:

```text
http://localhost:1313/open-neuroai-lab/
```

## GitHub Pages

This repo includes a GitHub Actions workflow at `.github/workflows/deploy.yml`.

Before publishing, edit `hugo.yaml`:

```yaml
baseURL: https://Zihan-Zoe.github.io/open-neuroai-lab-v2/
params:
  socialIcons:
    - name: github
      url: https://github.com/Zihan-Zoe/open-neuroai-lab-v2
```

Then push to `main` and enable GitHub Pages with **GitHub Actions** as the source.
