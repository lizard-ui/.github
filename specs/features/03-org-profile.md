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
* Link to **lizard-ui/lizard-ui**, **npm**, and **docs/**.
* Use **`.github/icon-cropped.png`** and hero screenshots **`.github/screenshot.png`** / **`.github/screenshot_dark.png`** (org profile uses `<picture>` + `prefers-color-scheme`; raw URLs on `lizard-ui/.github` `main`).
* Keep maintainer-only operational detail out of the public profile.

Preview: push to `main` and open [github.com/lizard-ui](https://github.com/lizard-ui).
