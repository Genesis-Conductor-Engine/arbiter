# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Visual Hierarchy in Architecture Diagrams
**Learning:** In infrastructure documentation, complex "dual nature" systems benefit from a central visual anchor. Using specific Mermaid styles (double-circle nodes and distinctive colors) for the core orchestration component creates an immediate focal point that anchors the surrounding layers.

**Action:** Use `node((Name))` syntax and `style Name fill:#f96,stroke-width:4px` to distinguish primary orchestration nodes in architecture diagrams for better visual scannability.
