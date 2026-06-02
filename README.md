# APNewsArchive

A single-file browser app that scans five independent breaking-news feeds by default, compares the top 10 normalized stories against a configurable p2fk keyword, and etches only the missing stories one at a time after each prior transaction fully confirms. Story deduplication now uses a stable URL-hash identifier instead of Google GUID extraction, and the app is designed to run directly from `file://` in a modern browser.
