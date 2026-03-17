# AGENTS.md

## Purpose

This file defines the working rules for contributors and coding agents in `paper-seal-studio-site`.

## Rules

1. When any task is completed, send a Windows system notification with the exact message: `paper-seal-studio-site: Tarea terminada`.
2. Preserve the brand direction described in [VISION.md](/d:/src/paper-seal-studio-site/VISION.md): premium, gallery-grade, tactile, restrained, and editorial.
3. Treat Hugo as the source of truth. Prefer Hugo content, layouts, partials, shortcodes, and assets over adding unnecessary tooling or frameworks.
4. Keep the main navigation aligned with the defined sitemap:
   - `Exhibitions`
   - `The Studio`
   - `Find Us`
   - `Care & Framing`
5. Maintain the design system:
   - Primary color: `#000080`
   - Background: `#F9F7F2`
   - Text: `#333333`
   - Serif headings with a clean geometric sans for UI/body
6. Favor lightweight, maintainable CSS using Grid and Flexbox. Do not introduce heavy UI frameworks unless explicitly requested.
7. Keep the site responsive, with special attention to mobile usage for fair visitors.
8. For artwork pages, preserve the expected front matter structure:
   - `title`
   - `collection`
   - `vibe`
   - `paper`
   - `price_a3`
   - `image_main`
   - `image_mockup`
9. Default conversion flow is not a cart. Keep the reservation path oriented around WhatsApp and fair pickup unless the user asks to change the sales model.
10. Before making broad visual changes, check that they still feel intentional, high-end, and not generic template output.

## Working Preferences

- Prefer small, verifiable changes over broad speculative rewrites.
- Run Hugo build validation after meaningful template or content changes.
- Keep copy elegant and concise unless a long-form editorial page is explicitly intended.
- Use placeholder assets only when real assets are unavailable, and make that obvious in the implementation.

## Validation

After significant changes, prefer these checks:

```bash
hugo
npm run build
```
