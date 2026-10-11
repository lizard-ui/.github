---
type: Feature
title: GitHub automation
description: Dependabot, CODEOWNERS, issue forms, and Dependabot commit signer for lizard-ui org.
tags: [github, dependabot, automation, lizard-ui]
timestamp: 2026-10-11T00:00:00Z
---

# GitHub automation

Org-wide defaults in **lizard-ui/.github**:

| Asset | Role |
|-------|------|
| `.github/dependabot.yml` | Dependency update PRs for this meta-repo |
| `.github/workflows/dependabot-signature.yml` | `Co-authored-by` on Dependabot commits |
| `.github/CODEOWNERS` | Review ownership (`@charlite`) |
| `.github/ISSUE_TEMPLATE/*.yml` | Bug, feature, docs forms (reference **lizard-ui** package) |
| `.github/pull_request_template.md` | Default PR body |

Package repo **lizard-ui/lizard-ui** ships its own CI (`ci.yml`, `publish.yml`) and may mirror these issue templates.

Reference: [docs/README.md](../../docs/README.md).
