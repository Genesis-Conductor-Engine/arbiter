# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Visualizing System Mental Models
**Learning:** For infrastructure projects, technical architecture diagrams (e.g., Mermaid) are high-impact UX improvements. They allow users to quickly grasp the relationship between complex layers (like Bare-Metal and Kubernetes) which is often difficult to communicate through text alone.

**Action:** When a project involves multi-layered orchestration or hardware-to-software bridging, prioritize adding a Mermaid diagram with clear visual hierarchies (using subgraphs and styles) to help users build a correct mental model.
