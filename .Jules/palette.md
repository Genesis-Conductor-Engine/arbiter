# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-20 - Visual Hierarchy in Infrastructure Diagrams
**Learning:** In complex orchestration projects, Mermaid diagrams benefit significantly from visual hierarchy. Distinguishing the "Core" component using specific styling (different colors, thicker borders) provides immediate cognitive relief and helps users identify the primary system anchor within multiple layers.

**Action:** Use Mermaid `style` definitions and distinct node shapes (like double circles `((...))`) for primary architectural components in infrastructure documentation.

## 2026-05-22 - Semantic Node Shapes in Architecture Diagrams
**Learning:** Using semantic node shapes in Mermaid diagrams (e.g., stadium shapes `([ ... ])` for workloads and hexagons `{{ ... }}` for specialized scheduling logic) improves the cognitive speed at which a user differentiates between data/workload types and active processing components.

**Action:** Consistently apply stadium shapes for Kubernetes clusters and AI workloads, and hexagons for specialized components like Quantum Schedulers or VRAM pinning logic, while maintaining the double-circle for the orchestration core.
