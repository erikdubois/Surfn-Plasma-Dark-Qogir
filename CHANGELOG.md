# Changelog

## 2026.06.21 — repo standardisation

### What Changed

Added the standard project docs and corrected the README's dependency note.

### Technical Details

- Ships only `Surfn-Plasma-Dark-Qogir`, which `Inherits=Surfn-Plasma-Dark,breeze-dark,breeze,hicolor`.
  The theme therefore needs `surfn-plasma-dark-icons-git` present at runtime, but the
  packaging recipe currently has `depends=()` — a known gap, not fixed here.
- Added CLAUDE.md.

### Files Modified

- README.md, CHANGELOG.md, CLAUDE.md
