# IssuePulse Release Notes

Public release notes for [IssuePulse](https://app.issuepulse.io), one-click feedback links for newsletters.

**App:** [app.issuepulse.io](https://app.issuepulse.io) · **Website:** [issuepulse.io](https://www.issuepulse.io) · **Changelog:** [issuepulse.io/changelog](https://www.issuepulse.io/changelog)

## Latest release

**[v1.3.0](releases/v1/v1.3.0.md)** — 3 November 2026 — A faster dashboard that shows each page the moment you click.

## All releases

| Version | Date | Type | Summary |
|---|---|---|---|
| [v1.3.0](releases/v1/v1.3.0.md) | 2026-11-03 | Minor | Faster dashboard; loading previews on every page; busy states for search and saving |
| [v1.2.0](releases/v1/v1.2.0.md) | 2026-10-20 | Minor | Issues, issue scores, sponsored vs regular, weekly summary, CSV export |
| [v1.1.1](releases/v1/v1.1.1.md) | 2026-10-19 | Patch | Workspace settings protected; handle locks once links are in use |
| [v1.1.0](releases/v1/v1.1.0.md) | 2026-10-18 | Minor | App matches issuepulse.io; real all-time trend; help center links |
| [v1.0.0](releases/v1/v1.0.0.md) | 2026-10-09 | Major | First public release |

For a short, one-page view of every version, see [CHANGELOG.md](CHANGELOG.md).

## How versions are numbered

IssuePulse uses [Semantic Versioning](https://semver.org): `MAJOR.MINOR.PATCH`.

- **Major** (`2.0.0`): big changes, or anything that changes how existing links or data behave.
- **Minor** (`1.1.0`): new features. Nothing you already use breaks.
- **Patch** (`1.0.1`): bug fixes and small improvements only.

## How this repo is organised

```
README.md            you are here: latest release and the full list
CHANGELOG.md         every version on one page, newest first
RELEASING.md         how to add a new release
releases/
  v1/                every 1.x.x release
    v1.0.0.md
  v2/                every 2.x.x release (when it exists)
templates/
  major-minor.md     starting point for a major or minor release
  patch.md           starting point for a patch release
```

Each major version gets its own folder, and each release inside it gets its own file.
