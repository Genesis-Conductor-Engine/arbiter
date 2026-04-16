# Palette's Journal

This journal contains critical UX/accessibility learnings discovered during the development of this application.

## 2026-05-18 - Documentation as the Primary Interface
**Learning:** For infrastructure or backend projects without a functional frontend, the `README.md` serves as the primary User Experience (DX/UX). In these cases, micro-UX improvements shift from ARIA labels to scannability, clarity of project status, and informative (non-redundant) feature lists.

**Action:** Treat the `README.md` as the landing page. Use visual status indicators (badges), scannable bullet points with representative emojis, and ensure that headers provide a clear path for the user to understand the project's utility and maturity.

## 2026-05-19 - Visual Hierarchy in Technical Diagrams
**Learning:** Complex orchestration logic is often difficult to parse from text alone. Mermaid diagrams provide immediate clarity, but can become cluttered. Using Mermaid `style` definitions (fill, stroke) creates a visual hierarchy that guides the user's eye to the most critical system components (like the control plane).

**Action:** When adding architecture diagrams to documentation, use custom styles to highlight primary components and differentiate between different layers (e.g., Kubernetes vs. Hardware) to improve cognitive scanability.
