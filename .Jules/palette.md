# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-20 - Standardized Visual Identity for Core Orchestration Components
**Learning:** In architecture diagrams for the `arbiter` ecosystem, users can more quickly identify the primary orchestration hub when it has a distinct visual style from its dependencies and consumers.

**Action:** When representing the 'Arbiter Core' in Mermaid diagrams, use double-circle syntax `((Arbiter Core))` and apply a high-contrast style: `fill:#f96,stroke-width:4px`.
