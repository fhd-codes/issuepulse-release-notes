# How to add a release

## 1. Pick the version number

Start from the latest version in [CHANGELOG.md](CHANGELOG.md) and bump one part:

| What changed | Bump | Example |
|---|---|---|
| Something that changes how existing links or data behave, or a big redesign | Major | `1.4.2` → `2.0.0` |
| New features, nothing existing breaks | Minor | `1.4.2` → `1.5.0` |
| Bug fixes only | Patch | `1.4.2` → `1.4.3` |

Bumping a part resets the parts to its right to zero.

## 2. Create the release file

- Copy [templates/major-minor.md](templates/major-minor.md) for a major or minor release, or [templates/patch.md](templates/patch.md) for a patch.
- Save it as `releases/v<MAJOR>/v<VERSION>.md`, for example `releases/v1/v1.1.0.md`.
- Starting a new major version? Create its folder first, for example `releases/v2/`.

## 3. Update the index files

- **CHANGELOG.md**: add a short entry at the top, linking to the new file.
- **README.md**: update "Latest release" and add a row to the top of the "All releases" table.

## 4. Tag it (optional)

Create a GitHub Release with the tag `v<VERSION>` and paste the release file's content as the description.

## Writing tips

- Write for newsletter creators, not developers. Say what changed for them, not how the code changed.
- Leave out empty sections.
- Only list what is shipped and committed. No plans, roadmap items or "coming soon".
- Don't name internal files, database tables or commit hashes.
- Don't describe security problems in enough detail to exploit them. Say what is now protected.
