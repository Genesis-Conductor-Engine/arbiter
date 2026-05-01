# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-20 - Visual Hierarchy in Architecture Diagrams
**Learning:** In complex orchestration diagrams, the primary component (e.g., 'Arbiter Core') can get lost among infrastructure and cloud-native layers. Using specific Mermaid styles (fill color, stroke width) and unique node shapes (double-circle) establishes a clear visual focal point.

**Action:** For the primary orchestration node in Mermaid diagrams, use double-circle syntax `((Node))` and apply styles `fill:#f96,stroke-width:4px` to distinguish it from secondary components.
