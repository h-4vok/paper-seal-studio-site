# Paper Seal Studio Site

Marketing site and exhibition catalogue for Paper Seal Studio, built with Hugo.

## Stack

- Hugo Extended
- npm scripts as a simple task runner

## Getting started

```bash
npm run dev
```

That starts the local Hugo server with drafts enabled at `http://localhost:1313`.

## Available scripts

- `npm run dev`: run the local development server with drafts enabled.
- `npm run build`: create an optimized production build in `public/`.
- `npm run build:drafts`: build the site including draft content.
- `npm run preview`: run Hugo's server without draft mode.
- `npm run new:piece`: scaffold a new exhibition piece at `content/exhibitions/piece-name.md`.
- `npm run new:page -- <path>`: create additional content with Hugo.

## Content structure

```text
content/
├── _index.md
├── exhibitions/
│   ├── _index.md
│   └── piece-name.md
├── the-studio/
│   └── index.md
├── find-us/
│   └── index.md
└── care-and-framing/
    └── index.md
```

## Notes

- Navigation follows the sitemap defined in `VISION.md`.
- The current implementation is a lean custom Hugo starter, ready to be expanded into the full brand experience.
