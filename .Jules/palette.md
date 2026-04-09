# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-04-09 - GitHub Markdown Anchor Links for Emojis
**Learning:** GitHub Markdown anchor links for headers containing emojis must strip the emojis and special characters to function correctly. For example, `## 🔭 Overview` maps to `#overview`, not `#-overview` or `#🔭-overview`.
**Action:** Always strip emojis and special characters when creating Table of Contents links for headers that use them.
