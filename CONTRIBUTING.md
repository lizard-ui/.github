# Contributing — lizard-ui organization

Thanks for helping improve **Lizard UI** and org governance.

## Where to contribute

| Change | Repository |
|--------|------------|
| Components, themes, `website/`, `docs/`, `knowledge/`, npm release | [lizard-ui/lizard-ui](https://github.com/lizard-ui/lizard-ui) |
| Org profile, org-wide issue templates, this meta-repo | [lizard-ui/.github](https://github.com/lizard-ui/.github) |

Follow [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Package repo workflow

```bash
git clone https://github.com/lizard-ui/lizard-ui.git
cd lizard-ui
bun install
bun run typecheck && bun run test && bun run build
```

See the package [CONTRIBUTING.md](https://github.com/lizard-ui/lizard-ui/blob/main/CONTRIBUTING.md) and [knowledge/contributing.md](https://github.com/lizard-ui/lizard-ui/blob/main/knowledge/contributing.md).

## Meta-repo workflow

1. Branch from `main` on **lizard-ui/.github**.
2. Update `profile/README.md` for public org messaging; keep specs in `specs/features/`.
3. Open a PR using the pull request template.

## Commits

[Conventional commits](https://www.conventionalcommits.org/) preferred. Record user-visible org changes in [CHANGELOG.md](CHANGELOG.md) and [specs/log.md](specs/log.md).

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
