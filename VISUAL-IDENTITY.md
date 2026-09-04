# Visual Identity Direction

## 90 Days of AI Engineering

**Status:** Creative direction  
**Owner:** Theo Goulart  
**System principle:** Learn → Build → Document → Share

This document defines the visual system for the 90-day journey. It is a direction for future assets, not a request to generate or implement graphics at this stage.

## 1. Core idea

### A visible engineering process

The identity should feel like an engineer's working notebook made public: precise, calm, structured, and progressively richer as evidence accumulates.

The visual language combines a dark technical canvas with restrained signal colors and a modular grid. It should communicate progress through structure, not through decoration.

### Brand attributes

| Attribute | Visual implication |
| --- | --- |
| Professional | High contrast, generous whitespace, disciplined alignment |
| Technical | Monospaced labels, grid references, precise metadata |
| Continuous | Repeated day marker and incremental numbering |
| Curious | One focused accent color used as a signal of discovery |
| Minimal | No decorative badges, mascots, stock imagery, or visual noise |

## 2. Repository banner

### Specification

- **Canvas:** 1,584 × 396 px, 4:1 ratio.
- **Safe area:** keep essential content within the central 1,320 × 300 px area; allow generous edge margins for different GitHub crops.
- **Background:** `#0B0F14` (near-black blue charcoal).
- **Format:** PNG or JPG, exported at 2× where the source tool supports it.

### Composition

Use a quiet, left-aligned composition:

```text
┌──────────────────────────────────────────────────────────────┐
│  90 DAYS / AI ENGINEERING                         [01—90]     │
│                                                              │
│  A public record of building with AI                         │
│  Learn → Build → Document → Share                             │
│                                                              │
│  THEO GOULART                                      2026       │
└──────────────────────────────────────────────────────────────┘
```

- **Eyebrow:** `90 DAYS / AI ENGINEERING`, small uppercase technical label.
- **Primary title:** `A public record of building with AI`.
- **Signature line:** `Learn → Build → Document → Share`.
- **Metadata:** `THEO GOULART` and `2026` as quiet footer information.
- **Progress motif:** a thin segmented line or 90-cell grid aligned to the right edge. It must remain abstract until real progress exists; do not imply completed days.

### Hierarchy

1. Primary title
2. Series label
3. Signature line
4. Author and year
5. Progress motif

The title should be readable at thumbnail size. The progress motif is supporting structure, never the focal point.

## 3. Open Graph image

### Specification

- **Canvas:** 1,200 × 630 px, 1.91:1 ratio.
- **Safe area:** 96 px minimum on every side.
- **Background:** `#0B0F14`.
- **Use:** repository shares, LinkedIn, Discord, and Twitter/X.

### Layout

Use a two-zone composition with a 65/35 split:

- **Left zone:** title and signature, vertically centered.
- **Right zone:** a precise 3 × 3 modular grid, with one accent cell and a small `01—90` marker. The grid represents a system in progress, not a chart of fabricated results.

### Exact copy

```text
90 DAYS OF AI ENGINEERING
Learn → Build → Document → Share
THEO GOULART · 2026
```

Do not add slogans, platform logos, certification claims, or a long project description. The image must remain legible when reduced in a social preview.

## 4. Official daily template

Every daily asset should be recognizably part of the same series, whether it is a repository image, LinkedIn card, presentation slide, or future website module.

### Exact day lockup

```text
DAY 01 / 90
```

Use the same format for every entry, including leading zeroes: `DAY 02 / 90` through `DAY 90 / 90`.

### Layout

- **Top-left:** `90 DAYS / AI ENGINEERING` in the eyebrow style.
- **Center-left:** `DAY 01 / 90` as the dominant element.
- **Below the day marker:** one short topic title, maximum two lines.
- **Bottom-left:** one metadata line: `LEARN · BUILD · DOCUMENT · SHARE` or the applicable stages.
- **Right side:** a restrained vertical rule and the progress motif.
- **Footer:** date, repository path, or project name—only when useful.

### Recommended card sizes

- Social square: 1,080 × 1,080 px
- Social landscape: 1,200 × 630 px
- Presentation: 1,920 × 1,080 px

The system is responsive: preserve the same hierarchy and alignment, not a rigid pixel-for-pixel composition.

## 5. Signature

### Primary signature

**Learn → Build → Document → Share**

Keep this as the official signature. It is clear, memorable, and describes the actual operating model of the project. The arrows express continuity and feedback, while the four verbs remain useful as labels in any medium.

### Short form

For narrow layouts, use **L → B → D → S** only as a secondary graphic notation. Never use it without the full signature somewhere in the same piece.

## 6. Visual language

### Color palette

| Role | Color | Use |
| --- | --- | --- |
| Ink | `#0B0F14` | Primary background |
| Surface | `#121923` | Cards, panels, and alternate surfaces |
| Line | `#263241` | Rules, grids, and dividers |
| Text | `#F2F5F7` | Primary text |
| Muted | `#9AA7B5` | Metadata and secondary text |
| Signal | `#63D6C5` | One active state, link, or progress highlight |
| Caution | `#E4B86A` | Limitations, pending work, or review states only |

Use the palette proportionally: approximately 75% dark neutrals, 20% light text and surfaces, and no more than 5% accent color. The caution color is exceptional, not decorative.

### Typography

- **Primary display:** `Inter` or `IBM Plex Sans`, semibold, with tight but comfortable tracking.
- **Technical labels:** `IBM Plex Mono` or `JetBrains Mono`, uppercase, 11–14 px in digital cards.
- **Body text:** the primary display family, regular weight, 1.5 line height.

Use no more than two families. Avoid condensed display faces, futuristic type, all-caps paragraphs, and excessive font weights.

### Spacing and grid

- Base unit: **8 px**.
- Standard outer margin: **64 px** on large canvases; **32 px** on social cards.
- Text blocks: maximum **60–72 characters** per line.
- Use a 12-column grid for banners, social landscape assets, and slides.
- Align labels, titles, rules, and footer metadata to the same left edge.

### Icons and graphics

- Use simple 1.5–2 px monoline icons with rounded joins.
- Prefer arrows, brackets, nodes, cursors, and grid cells over literal AI imagery.
- Never use robot heads, glowing brains, circuit-board clichés, or decorative 3D renders.
- Keep diagrams functional: every line or shape must clarify sequence, structure, or evidence.

### Illustration and imagery

Illustration is optional. When needed, use abstract system diagrams, documentation fragments, or restrained technical diagrams in the same palette. Avoid stock photos, lifestyle imagery, neon effects, and gradients that compete with the information.

## 7. Reuse across channels

| Channel | Adaptation |
| --- | --- |
| GitHub | Banner, README tables, day folders, and progress states use the same labels, palette, and signature. |
| LinkedIn | Use the daily lockup as the opening frame or cover card; keep one idea per post and link back to the corresponding day. |
| Presentations | Treat each day or project as a modular slide with the same eyebrow, day marker, grid, and footer metadata. |
| Future website | Turn the progress motif into an honest 90-day timeline; reuse the same tokens for surfaces, type, links, and states. |

The system should scale by recombination: the same small set of tokens creates different assets without making every channel look identical.

## 8. Design principles

1. **Evidence before ornament.** Visuals support the work; they do not manufacture importance.
2. **One signal at a time.** Use the accent color to direct attention to one active element.
3. **Progress must be earned.** Never fill a day, grid cell, or metric before the work exists.
4. **Structure creates memorability.** Repetition of the lockup, grid, and signature builds recognition.
5. **Readable first.** If a visual flourish reduces clarity at thumbnail size, remove it.
6. **Quiet confidence.** Let consistency and specificity communicate ambition.

## Design rationale

The near-black blue canvas gives the project a durable technical foundation without the theatrical feel of a neon or gamer aesthetic. A single mint signal color suggests movement and discovery while keeping the system restrained. Monospaced labels add engineering character; a humanist sans-serif keeps the experience approachable and readable.

The repeated `DAY NN / 90` lockup makes the series instantly recognizable and turns time into a visual system. The modular grid provides a memorable signature that can move from a repository banner to a social card or website timeline without adding complexity. Most importantly, the identity treats progress as evidence: visual completion states are reserved for work that has actually happened.

