# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-20 - Visual Hierarchy in Infrastructure Diagrams
**Learning:** In complex orchestration projects, Mermaid diagrams benefit significantly from visual hierarchy. Distinguishing the "Core" component using specific styling (different colors, thicker borders) provides immediate cognitive relief and helps users identify the primary system anchor within multiple layers.

**Action:** Use Mermaid `style` definitions and distinct node shapes (like double circles `((...))`) for primary architectural components in infrastructure documentation.

## 2026-05-21 - Semantic Node Shapes for Infrastructure DX
**Learning:** In technical documentation for orchestration systems, using semantic node shapes in Mermaid diagrams (e.g., stadium shapes `([ ... ])` for Kubernetes/Workloads and hexagons `{{ ... }}` for specialized algorithms or hardware pinning) provides immediate visual cues about the nature of the component. This reduces the cognitive load required to understand the relationship between software and hardware layers.

**Action:** Apply stadium shapes for high-level abstractions (K8s, clusters) and hexagons for specialized/low-level logic (Schedulers, VRAM pinning) in infrastructure diagrams.
