# nomba-docs-rust

Documentation site for the **[nomba-rust](https://github.com/RightFix/nomba-rust)** SDK — an unofficial Rust client for the Nomba payments API.

This is a static site (plain HTML/CSS/JS) published with GitHub Pages at:

**https://RightFix.github.io/nomba-docs-rust/**

## Structure

- `index.html` — overview
- `getting-started.html` — install, feature flags, sync vs async, error handling
- `features.html` — pagination, card-payment flow, webhooks, reliability
- `resources.html` — full API reference (99 endpoints, 15 resource groups)
- `changelog.html` — version history
- `assets/` — shared stylesheet and script

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
