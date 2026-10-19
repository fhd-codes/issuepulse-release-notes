# Changelog

Every IssuePulse release, newest first. Each entry links to its full release notes.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and versions follow [Semantic Versioning](https://semver.org).

## [1.2.0] — 2026-10-20

Track each issue you send: its own links, a score, sponsored vs regular, a weekly summary and CSV export. [Full release notes →](releases/v1/v1.2.0.md)

### Added
- Issues: log each send and copy its own links, so every vote and embed open is tied to that issue.
- Issue score from -100 to +100, shown once an issue has 5 votes.
- Sponsored vs regular: how sponsored issues score against your regular ones, from 3 scored issues of each kind.
- Positive, neutral or negative setting for each link, used by issue scores.
- "This week" summary on the dashboard: votes, top topic, most requested topic, best and weakest issue, new comments.
- CSV export of votes, comments and issues in Settings.

## [1.1.1] — 2026-10-19

Workspace settings are protected, and your handle locks once your links are in use. [Full release notes →](releases/v1/v1.1.1.md)

### Fixed
- Your workspace handle locks once a reader votes on or opens your links, so links in sent issues keep working. Topic URLs already worked this way.
- Workspace settings can only be changed from the IssuePulse settings page.

## [1.1.0] — 2026-10-18

The app now matches issuepulse.io, and All time really means all time. [Full release notes →](releases/v1/v1.1.0.md)

### Added
- Trend chart "All time" covers every day since a topic was created, scrolling sideways past 90 days.
- Embed opens count whatever format the topic is set to.
- "Learn more" links from each setting to its help center article; Help center and What's new in the sidebar.
- Release number at the bottom of the sidebar.
- IssuePulse logo, browser-tab icon and a small "Feedback by IssuePulse" line on the reader thank-you page.
- Terms and Privacy links on sign-up; how to delete your account in profile settings.

### Changed
- Copy format is remembered per topic and starts on the topic's own format.
- Colours and headline type match the website; small grey text is easier to read.
- The embed's "powered by IssuePulse" link goes to issuepulse.io.

### Removed
- The in-app Guide page, replaced by the help center.

### Fixed
- Comments total stopping at 50.
- "1 votes" / "1 opens" in the chart legend.
- Trend chart days around clock changes.

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
