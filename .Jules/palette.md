# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-18 - Visualizing Orchestration with Mermaid
**Learning:** For infrastructure projects managing multiple layers (hardware, cluster, logic), a Mermaid architecture diagram provides an immediate mental model that text alone cannot achieve. Using custom 'style' definitions (like `fill` and `stroke-width`) helps distinguish the project's core component from the environments it orchestrates.

**Action:** Include Mermaid diagrams in the README to represent system architecture. Use color-coding and line thickness to create a visual hierarchy that highlights the project's role within the larger stack.
