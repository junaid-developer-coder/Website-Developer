<p align="center">
  <img src="assets/logo-horizontal.svg" alt="Antigravity Setup Guide" width="360">
</p>

<p align="center">
  Step-by-step, feature-by-feature installation of Google Antigravity on <strong>Windows</strong> and <strong>Linux</strong>.
</p>

<p align="center">
  <a href="https://YOUR-USERNAME.github.io/antigravity-setup-guide/">Live site</a> ·
  <a href="https://antigravity.google/download">Official downloads</a> ·
  <a href="CONTRIBUTING.md">Contribute</a>
</p>

> Community project. Not affiliated with, endorsed by or supported by Google. Google and Antigravity are trademarks of Google LLC. The logo in this repository is an original mark, not Google's logo.

## What it covers

| Feature | Windows | Linux |
| --- | --- | --- |
| Antigravity 2.0 desktop app | `.exe` installer (x64, ARM64) | `.tar.gz` (x64, ARM64) |
| Antigravity CLI | PowerShell or CMD one-liner | `curl … \| bash` |
| Antigravity IDE (standalone) | `.exe` installer | `.tar.gz` |
| Editor extensions | VS Code, Visual Studio, JetBrains, Zed | VS Code, JetBrains, Zed |
| Python SDK | venv + official repo | venv + official repo |

Versions listed when written (19 Sep 2026): Antigravity 2.0 v2.14.0, CLI v1.2.0, IDE v2.5.5, SDK v0.1.16. Always confirm on the [official download page](https://antigravity.google/download).

## Quick start (CLI)

**Linux**
```bash
curl -fsSL https://antigravity.google/cli/install.sh | bash
```

**Windows (PowerShell)**
```powershell
irm https://antigravity.google/cli/install.ps1 | iex
```

Prefer to read scripts before running them? The site shows how.

## Run the site locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` deploys on every push to `main`.
4. Replace every `YOUR-USERNAME` with your GitHub username.


## Logo

`<img src="assets/logo-mark.svg" > is a floating orb above a curved base: an object lifted off the ground. The horizontal version pairs it with the project name. Both are original artwork released under the repository's MIT license.

## License

MIT. See [LICENSE](LICENSE).
