# ad-templates

Inline HTML5 banner starters kept vendor-compliant for Adform, Google DV360, and Xandr.

## Templates
- `templates/adform/basic-300x250`: Includes manifest-ready markup and clickTag logic per Adform specs.
- `templates/google/basic-300x250`: Minimal DV360-safe creative with inline assets.
- `templates/xandr/basic-300x250`: IAB clickTag implementation compatible with Xandr/AppNexus.

## Workflow
- Duplicate the required size folder, replace copy and assets, leave clickTag handling intact.
- Test creatives by opening `index.html` directly in a browser.
- Respect root agent files: `.cursorrules`, `.codex/`, `.claude/`, and `CLAUDE.md`.
