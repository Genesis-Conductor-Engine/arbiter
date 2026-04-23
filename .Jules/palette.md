# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Accessible Badges and Alert Blocks
**Learning:** Standard badges often lack context for screen readers. Using descriptive alt-text (e.g., "License: MIT - This project is open-source...") provides necessary context. Additionally, GitHub-native Alert blocks (`[!CAUTION]`) are more effective for signaling risk than simple text or badges alone.

**Action:** Always provide descriptive alt-text for badges that explain the *implication* of the badge, not just its label. Use GitHub Alert blocks for critical project status or usage warnings.
