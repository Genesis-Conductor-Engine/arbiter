# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-20 - Visualizing System Architecture for DX
**Learning:** In infrastructure-heavy repositories, the cognitive load to understand system interactions is high. Mermaid diagrams with styled core components (e.g., using `fill` and `stroke-width`) act as a visual anchor, significantly improving the "Time to Understanding" for developers.

**Action:** Use Mermaid `subgraph` blocks to represent different system layers (Cloud Native, Orchestration, Infrastructure) and apply distinct styling to the primary orchestration node to establish a visual hierarchy.
