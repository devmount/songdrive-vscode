# Changelog

All notable changes to the SongDrive Syntax Support extension will be documented in this file.

## [0.2.0]

- Reworked grammar to match the actual SongDrive syntax: song part markers (`--v`, `--c`, `--b`, ...) and individual chords are now tokenized distinctly, instead of one generic line each
- Chords and markers are colored using the active theme's string/comment colors
- Added bracket matching, auto-closing pairs, and surrounding pairs for `()`, `[]`, `{}`
- Added `docs/` with the SongDrive syntax reference and example song files
- Raised the minimum supported VS Code version to `1.75.0`

## [0.1.0]

🚀 Initial release.

- Syntax highlighting for SongDrive song files (`.songdrive`, `.sd`)
