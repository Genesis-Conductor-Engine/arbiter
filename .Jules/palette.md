# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-04-28 - High-Visibility Warnings for Experimental Projects
**Learning:** For infrastructure tools that interact with bare-metal or high-performance hardware, standard "Experimental" badges can be easily overlooked. Using GitHub Alert blocks (`[!CAUTION]`) provides much stronger visual weight and immediate recognition of the project's maturity level, reducing the risk of improper use in production.

**Action:** Prefer GitHub Alert blocks over status badges when communicating critical usage warnings or experimental status in repository documentation.
