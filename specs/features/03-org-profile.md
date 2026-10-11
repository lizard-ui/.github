---
type: Feature
title: Organization profile
description: Public visitor-facing profile README on the lizard-ui org homepage.
tags: [github, organization, profile, lizard-ui]
timestamp: 2026-10-11T00:00:00Z
---

# Organization profile

GitHub renders **`profile/README.md`** from the **lizard-ui/.github** repository as the public org homepage.

## Content contract

* Lead with **what Lizard UI is** (React component library on npm).
* Link to **lizard-ui/lizard-ui**, **npm**, and **docs/** — not generic template placeholders.
* Use assets from **`.github/icon-cropped.png`** and **`.github/screenshot.png`** in this meta-repo (raw URLs on `lizard-ui/.github` `main`).
* Keep maintainer-only operational detail out of the public profile.

Preview: push to `main` and open [github.com/lizard-ui](https://github.com/lizard-ui).

## Legacy `templates/` tree

The [`templates/`](../../templates/) directory and `scripts/init-from-template.*` remain from the upstream **open-templates** scaffold. The live **lizard-ui** org uses the **root** `profile/README.md` directly — do not run init against production org content without intent.
