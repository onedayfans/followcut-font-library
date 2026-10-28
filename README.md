# FollowCut Font Library

Public font asset catalog for FollowCut iOS. This repository contains font binaries, per-font license notices, source attribution, and a machine-readable manifest. It does not contain FollowCut application source code.

## Catalog

The app groups fonts into Traditional Chinese, Japanese, Korean, and English. Shared font IDs are listed once in `font-manifest.json`, so the app can download a shared asset once and use it in both language categories.

- 42 font files are included under `fonts/`.
- Every included font has its own complete notice under `licenses/`.
- `font-manifest.json` records each asset's ID, display name, category, upstream source, byte size, and SHA-256.
- `ATTRIBUTION.md` explains the source and license layout.

The requested font `獅尾福圓` is not included because a verifiable upstream source and license have not been identified.

## License and changes

Each font remains under its upstream license. See the corresponding file in `licenses/` before using or redistributing an asset. Open Font License (OFL) subsets use a distinct internal font name. LXGW ZhenKai is included unmodified to comply with its additional Reserved Font Name permission. The app's font display label does not replace the original copyright or license notice.

Font files are provided with their source URLs and authors in the individual license notices and manifest. This catalog is not an endorsement by upstream authors.
