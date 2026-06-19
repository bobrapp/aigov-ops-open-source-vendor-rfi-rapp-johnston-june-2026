# aigov-ops-open-source-vendor-rfi-rapp-johnston-june-2026

AIGovOps Foundation open-source Vendor RFI/RFP webapp — evidence-oriented vendor stack composer for Beacon & Umbrella, with auditor value model and neutral vendor sponsorship framework.

## Quick start

Open `index.html` from the repository root in a browser.

## What this is

A single-file static webapp that serves two lenses for AIGovOps Foundation vendor evaluation:

- Beacon lens: an unsigned evidence-receipt preview (SHA-256 over a canonical record), ready for Beacon Ed25519 + JCS signing.
- Umbrella lens: a vendor stack composer across audit, policy-as-code, gates/controls, dashboards, runtime guardrails, agent insight, and shipping code.

## Files

- index.html - the webapp
- auditor-value.md - evidence-oriented auditor value model
- vendor-sponsorship.md - neutral sponsorship model (sponsor the surface, not the score)
- .github/workflows/pages.yml - GitHub Pages deploy workflow

## Hosting

Enable GitHub Pages (Settings > Pages > Source: GitHub Actions). Once deployed, the site can be linked or embedded from the Beacon and Umbrella sites on www.aigovops-foundation.com.

## License

Apache-2.0.
