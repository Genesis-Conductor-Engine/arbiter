# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Visual Hierarchy in Architecture Diagrams
**Learning:** In complex infrastructure diagrams, users benefit from a clear "hero" component. Using Mermaid's `double-circle` node syntax and distinct `fill` colors (e.g., `#f96`) for the primary orchestration node creates an immediate focal point, reducing cognitive load when mapping system flows.

**Action:** When creating architecture diagrams, identify the primary component and apply unique styling (thicker strokes, distinct fills, or special node shapes) to distinguish it from supporting infrastructure.
