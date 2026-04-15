# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Visual Mental Models and Explicit Status
**Learning:** For complex infrastructure systems, a Mermaid architecture diagram provides an immediate mental model that text alone cannot achieve. Additionally, while badges provide quick status, GitHub Alert blocks (`> [!IMPORTANT]`) ensure critical maturity information (like "Experimental") is impossible to miss for screen readers and visual users alike.

**Action:** Supplement technical overviews with Mermaid diagrams to show system flow. Use descriptive alt-text for status badges (explaining the *implication* of the status), and use GitHub Alert blocks for high-visibility project warnings or status.
