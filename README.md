# APNewsArchive

A single-file browser app that scans the AP breaking-news feed, compares the top 10 stories against a configurable p2fk keyword, and etches only the missing stories one at a time after each prior transaction fully confirms. Google feed requests are proxied through corsproxy.io by default, while Google article links are unwrapped to direct AP URLs whenever possible before fetching.
