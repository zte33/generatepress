# GeneratePress

Version-controlled copy of the [GeneratePress](https://generatepress.com) WordPress theme by Tom Usborne / EDGE22 Studios LTD.

| | |
|---|---|
| **Version** | 3.6.1 |
| **Requires WordPress** | 6.5+ |
| **Tested up to** | 6.9 |
| **Requires PHP** | 7.4+ |
| **License** | GPL-2.0-or-later |

## Installation

**Git (recommended for dev/staging):**

```bash
cd wp-content/themes
git clone https://github.com/zte33/generatepress.git generatepress
```

The folder must be named `generatepress` so the theme slug matches and child themes (`Template: generatepress`) resolve correctly.

**Zip upload:** download the asset from the [latest release](https://github.com/zte33/generatepress/releases/latest) and upload via **Appearance → Themes → Add New → Upload Theme**.

**Build a clean zip from any ref:**

```bash
git archive --format=zip --prefix=generatepress/ -o generatepress.zip v3.6.1
```

Repo-only files (`README.md`, `.git*`) are excluded via `.gitattributes`.

## Updating

1. Download the new version from WordPress.org or generatepress.com.
2. Replace the repo contents with the new theme files (keep `README.md`, `LICENSE`, `.gitignore`, `.gitattributes`).
3. Commit as `Update GeneratePress to X.Y.Z`, tag `vX.Y.Z`, and publish a release.

Customizations belong in a child theme or plugin, not in this repo, so upstream updates stay a clean drop-in.

## Credits & License

GeneratePress © 2014–2025 EDGE22 Studios LTD, distributed under the [GNU GPL v2 or later](LICENSE). Based on [Underscores](https://underscores.me/) © Automattic, Inc. Bundled third-party asset licenses are listed in `readme.txt`.
