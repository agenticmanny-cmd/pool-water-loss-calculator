# Pool Water Loss Calculator

Public-facing evaporation estimator for Benchmark Pools & Spas, hosted via GitHub Pages
at **poolwaterlosscalculator.benchmarkpools.com**.

This repo intentionally contains only the deployable page (`index.html`) and the
`CNAME` file for the custom domain. It has no diagnostic logic and no customer data.

Source of truth / internal notes (backend spec, measurement guide, Wix setup guide,
leak diagnostic tool) live in:
`OneDrive/Documents/Pool Water Loss Project/`

## Updating the live page

1. Edit `OneDrive/Documents/Pool Water Loss Project/pool-water-loss.html`
2. Copy it over `index.html` in this repo
3. Commit and push to `main` — GitHub Pages redeploys automatically within a minute or two

## DNS

A CNAME record at the DNS host for `benchmarkpools.com` points
`poolwaterlosscalculator.benchmarkpools.com` → `agenticmanny.github.io`.
See `OneDrive/Documents/Pool Water Loss Project/WIX-SETUP.md` for the Wix button setup.
