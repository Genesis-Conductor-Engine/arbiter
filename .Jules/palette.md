# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Visual Hierarchy in Technical Docs
**Learning:** For complex infrastructure projects, cognitive load is significantly reduced by using Mermaid diagrams with intentional styling (e.g., `fill`, `stroke-width`) to highlight the core component. High-visibility GitHub Alerts (`[!CAUTION]`) are more effective than small badges for communicating critical project status (like "Experimental").

**Action:** Use Mermaid diagrams to visualize multi-layer systems and prefer GitHub Alerts for critical usage warnings to ensure they aren't overlooked.
