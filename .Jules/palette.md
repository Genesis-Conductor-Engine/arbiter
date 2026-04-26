# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-18 - High-Visibility Status Indicators
**Learning:** Standard badges for project status (e.g., "Experimental") can be easily overlooked in dense documentation. Using GitHub Alert blocks (e.g., `> [!CAUTION]`) provides significantly higher visual prominence and prevents user error by clearly marking non-production-ready software.

**Action:** Use GitHub Alert blocks for critical project status or safety warnings to ensure they are the first thing a user notices.
