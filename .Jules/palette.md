# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-20 - Visual Hierarchy in Infrastructure Diagrams
**Learning:** In complex orchestration projects, Mermaid diagrams benefit significantly from visual hierarchy. Distinguishing the "Core" component using specific styling (different colors, thicker borders) provides immediate cognitive relief and helps users identify the primary system anchor within multiple layers.

**Action:** Use Mermaid `style` definitions and distinct node shapes (like double circles `((...))`) for primary architectural components in infrastructure documentation.

## 2026-05-22 - Semantic Shapes and Accessibility in Diagrams
**Learning:** Architecture diagrams are more accessible and easier to parse when they use semantic node shapes (stadiums for workloads/clusters, hexagons for specialized logic) and explicit titles. Delineating layers with dashed borders (`stroke-dasharray`) improves visual separation between subgraphs.

**Action:** Always include a `--- title: [Text] ---` in Mermaid diagrams. Use `([ ... ])` for external/user entities and `{{ ... }}` for specialized algorithms or hardware pinning logic. Apply `style [ID] stroke-dasharray: 5 5` to subgraphs representing distinct architectural layers.
