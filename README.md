# Engine Release Doctor

Evidence-backed release troubleshooting for Unreal Engine developers and small studios.

**Live site:** https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/

## Limited free beta

Engine Release Doctor is accepting its first five qualified **operator-assisted Release Blocker Audits** for free.

You provide a compact sanitized evidence set from a concrete release failure. Engine Release Doctor performs the evidence review, deterministic diagnostic checks, AI-assisted operator assessment, report preparation, safety review, and retest interpretation.

A qualified audit can include:

- failure-domain classification;
- evidence-backed likely-cause ranking;
- ordered corrective or isolation steps;
- rollback and stop conditions; and
- a one-variable retest plan.

The current offer does not guarantee repair, storefront approval, turnaround time, automatic remediation, or comprehensive release certification.

[Review the beta scope and request an audit](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/#apply)

## Before sending evidence

Do not post private release evidence in GitHub issues.

For first contact, send only the smallest useful sanitized evidence set. Remove passwords, access tokens, signing secrets, credentials, private customer data, and unrelated proprietary source. Do not send a complete project or large packaged build initially.

Preserve technical context such as filenames, relative paths, engine and plugin versions, generated commands, timestamps, error codes, and the lines around the first meaningful failure.

## Troubleshooting resources

The public resource library includes controlled preflights and evidence checklists for:

- [Windows path-length exposure, executable capability, and target-machine policy](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/windows-long-path-release-risk.html)
- [Steam `steam_appid.txt` Shipping-depot hygiene](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/steam-appid-shipping-depot.html)
- [Shipping-build verification](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/verify-shipping-build.html)
- [Packaged runtime-dependency verification](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/verify-runtime-dependencies.html)
- [Windows executable-signing preflight](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/windows-signing-preflight.html)
- [Packaged crash evidence collection](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/unreal-crash-log-evidence.html)

[Browse all release troubleshooting resources](https://davisscholarshiphunt-beep.github.io/engine-release-doctor-site/resources/)

## Repository purpose

This repository contains the public website and educational resources. It does not contain the private diagnostic product or customer evidence.

Public content must:

1. address a specific evidenced Unreal release problem;
2. provide useful standalone guidance;
3. distinguish verified facts from hypotheses and troubleshooting tests;
4. link to primary sources for technical claims;
5. preserve the current approved offer and its limitations; and
6. never expose customer data, credentials, private logs, internal records, or private product source.

## Deployment

GitHub Pages publishes from the `main` branch and repository root.
