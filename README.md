# beeCaptions Updates

Public update channel for the [beeCaptions](https://github.com/Fadeawayyy)
macOS app. The compiled app polls `appcast.xml` in this repo at launch
and once per hour to discover new versions; when one is published, the
app shows a "Update available" sheet to the user with one-click
install.

- `appcast.xml` — Sparkle feed, regenerated automatically by
  `Scripts/release.sh ship` in the main app repo.
- GitHub Releases tagged `v<version>` carry the signed `.dmg` files
  Sparkle downloads.

Nothing here needs manual edits — the release script in the app repo
handles everything.
