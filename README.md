# iion Display Ad Tag

Self-hosted display ad tag for GAM third-party tag integration.

## Quick Start

1. Enable GitHub Pages on this repo (Settings → Pages → Source: main branch)
2. Your tag URL will be: `https://[username].github.io/iion-display-ad-tag/index.html`
3. Use this URL as the Third-Party Tag in GAM
4. Swap creatives by replacing files in `creatives/current/`

## Swapping Creatives

1. Replace `creatives/current/index.html` with your new creative
2. Place any assets in `creatives/current/assets/`
3. Commit and push
4. Cache-busting is automatic (timestamp-based)

## Structure

```
├── index.html              # Entry point (GAM points here) - DO NOT MODIFY
├── creatives/
│   └── current/
│       ├── index.html      # Your active creative
│       └── assets/         # Images, CSS, JS for your creative
└── archive/                # Store old creatives for reference
```
