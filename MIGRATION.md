# Prismtek Consolidation Status

This repository is being audited as part of the canonical Prismtek repository consolidation tracked in `codysumpter-cloud/prismtek-apps#359`.

Planned replacement: `codysumpter-cloud/prismtek-apps/services/buddy-agent`.

## Current state

- This repository is not the canonical Prismtek product monorepo.
- Recent maintenance has primarily concerned upstream fork synchronization.
- No repository will be deleted or archived until unique Prismtek code, tests, documentation, licenses, and active consumers are accounted for.

## Before retirement

1. Compare this fork against its upstream and the Buddy Agent destination.
2. Build a unique-content and license manifest.
3. Migrate any required Prismtek-specific changes with provenance.
4. Confirm no active consumer depends on this repository URL, package source, or checkout path.
5. Add a final supersession notice and `pre-archive-final` tag.
6. Archive the repository; do not delete it.

New canonical Buddy runtime work should target the consolidation destination rather than expanding this fork.
