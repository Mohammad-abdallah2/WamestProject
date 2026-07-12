# WAMEST — Design Tokens

Set these up as **Figma Styles / Variables** first, then everything stays consistent.

## Colors (from your logo)

| Token | Hex | Use |
|---|---|---|
| Charcoal | `#4A4A4A` | Primary — logo wordmark, footer bg, body text |
| Charcoal Deep | `#2E2E2E` | Headings, top bar, partners section bg |
| Teal | `#4A8B8C` | Secondary — logo "A", buttons, accents, links |
| Teal Dark | `#3A6E6F` | Button hover |
| Paper | `#F5F5F3` | Alt section background |
| White | `#FFFFFF` | Base background |
| Line | `#E2E2DE` | Borders, dividers |
| Muted | `#7A7A78` | Secondary text |

## Typography

**Display — Barlow Condensed** (headings, nav, buttons, stats)
- H1 / Hero: 76px, Bold 700, uppercase, line-height 0.98
- H2 / Section: 52px, Bold 700, uppercase, line-height 1.06
- H3 / Footer: 20px, Semibold 600, uppercase, letter-spacing 0.1em
- Nav link: 17px, Semibold 600, uppercase, letter-spacing 0.08em
- Button: 16px, Semibold 600, uppercase, letter-spacing 0.12em
- Eyebrow: 14px, Semibold 600, uppercase, letter-spacing 0.18em
- Stat number: 44px, Bold 700

**Body — Archivo** (paragraphs, lists, links)
- Lede: 16–17px, Regular 400, line-height 1.6
- Body: 15px, Regular 400
- Small / footer: 14.5px
- Caption / copyright: 13.5px

## Layout

- Container max-width: **1240px**
- Gutter: 48px desktop → 20px mobile
- Section padding: 120px top/bottom desktop → 70px mobile
- Split sections: 2 columns, 1fr / 1fr, 80px gap
- Grid: 12 columns for Figma frames

## Breakpoints

| Frame | Width |
|---|---|
| Desktop | 1440px |
| Laptop | 1280px |
| Tablet | 1024px (nav → burger) |
| Mobile | 375px |

## Components to build in Figma

- Button — Outline / Solid / Ghost (each with Default + Hover)
- Nav link — Default / Hover / Active (2px teal underline)
- Eyebrow label — 34×3px teal dash + uppercase text
- Slide (hero) — image, dark scrim, text block, CTA
- Split block — image with 2px teal offset frame + text column
- Partner card — 210×120px white tile, grayscale → color on hover
- Footer column — title with 44×2px teal underline

## Signature detail

The **2px teal outline frame offset 22px behind each section image** — it echoes the "Λ" in the logo. Keep it. It's the one thing that makes the page recognizably WAMEST.
