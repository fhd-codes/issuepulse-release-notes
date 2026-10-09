# Changelog

Every IssuePulse release, newest first. Each entry links to its full release notes.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and versions follow [Semantic Versioning](https://semver.org).

## [1.0.0] — 2026-10-09

First public release. [Full release notes →](releases/v1/v1.0.0.md)

### Added
- One-click feedback links per topic, with an optional reader comment after voting.
- Editable link labels and a choice of 3 or 5 links per topic.
- Dashboard home with totals.
- Topics table with search, copy-format filter, sorting and paging.
- Topic detail page with vote breakdown, trend chart (7/14/30/90 days or all time), tracking links and reader comments.
- Four copy formats: Embed, Linked, Markdown and Plain.
- Embed open counting, filtered for scanners and deduplicated over 5 minutes.
- In-app guide and settings pages (workspace handle, profile, password).

### Changed
- Every page now works on phones.
- Shared design across buttons, cards, badges and dialogs.
- Older links (such as `/loved`) keep working after the move to editable labels.

### Removed
- Unused top-bar search and notification bell.
- Google and Apple sign-in buttons.
- "Billing & Payments" menu item.

### Fixed
- Cursor jumping out of form fields while typing in dialogs.
- Topics search box losing focus while typing.
- Click-through figure showing more than 100%.
- Several layout, chart and accessibility issues. See the full notes.

### Security
- Text on the public vote page is escaped.
- Read-only workspaces are enforced on every topic and handle change.
