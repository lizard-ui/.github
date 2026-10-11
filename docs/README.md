# Documentation — lizard-ui org GitHub configuration

Reference for workflows, issue templates, and pull request defaults in **lizard-ui/.github**.

Package CI and publish workflows live in [lizard-ui/lizard-ui](https://github.com/lizard-ui/lizard-ui/tree/main/.github/workflows).

## Workflows

| Document | Source file | Summary |
|----------|-------------|---------|
| [Dependabot commit signer](dependabot-signature-workflow.md) | [`.github/workflows/dependabot-signature.yml`](../.github/workflows/dependabot-signature.yml) | Amends Dependabot PR commits with a `Co-authored-by` trailer |

## Issue templates

Forms under [`.github/ISSUE_TEMPLATE/`](../.github/ISSUE_TEMPLATE/). Prefer filing **library bugs** on the package repo; org forms support both repos.

| Document | Source file | Default title | Labels |
|----------|-------------|---------------|--------|
| [Bug report](bug-report-issue-template.md) | [`bug_report.yml`](../.github/ISSUE_TEMPLATE/bug_report.yml) | `[Bug]:` | `bug`, `triage` |
| [Feature request](feature-request-issue-template.md) | [`feature_request.yml`](../.github/ISSUE_TEMPLATE/feature_request.yml) | `[Feature]:` | `enhancement`, `triage` |
| [Documentation issue](documentation-issue-template.md) | [`documentation.yml`](../.github/ISSUE_TEMPLATE/documentation.yml) | `[Docs]:` | `documentation`, `triage` |

## Pull request template

| Document | Source file |
|----------|-------------|
| [Pull request template](pull-request-template.md) | [`.github/pull_request_template.md`](../.github/pull_request_template.md) |

## Related

| File | Role |
|------|------|
| [`.github/dependabot.yml`](../.github/dependabot.yml) | Dependency update PRs (meta-repo) |
| [`.github/CODEOWNERS`](../.github/CODEOWNERS) | Default review ownership |

See [README.md](../README.md) and [INSTRUCTIONS.md](../INSTRUCTIONS.md).

---

**README** | [Dependabot commit signer](dependabot-signature-workflow.md) | [Bug report](bug-report-issue-template.md) | [Feature request](feature-request-issue-template.md) | [Documentation issue](documentation-issue-template.md) | [Pull request template](pull-request-template.md)
