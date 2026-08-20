# CalmDesk — Landing Page (OIBSIP Web Dev, Level 1, Task 1)

A static landing page for **CalmDesk**, a concept study companion for students during exam season. Instead of being a full productivity suite, CalmDesk focuses on three things: a study timer with built-in breaks, quick mood check-ins, and short guided breathing resets between study blocks.

This is a self-designed concept built for the OIBSIP Web Development internship, Level 1 – Task 1 (Landing Page).

## Live Preview

Open `index.html` directly in any browser — no build step, no dependencies beyond a Google Fonts link.

## Tech Stack

- HTML5
- CSS3 (Flexbox + Grid, no JavaScript, no frameworks)
- Google Fonts: Space Mono (display) + Work Sans (body)

## Design Concept

The page leans into a "notebook / exam paper" visual world rather than a generic SaaS template:

- **Palette:** sage-paper background, deep forest-charcoal ink text, a golden highlighter accent for calls-to-action, and a dusty coral used sparingly for the testimonial "tape" detail.
- **Typography:** Space Mono (typewriter-style monospace) for headlines and labels, paired with Work Sans for body copy.
- **Signature element:** a pure-CSS "breathing circle" in the hero that slowly expands and contracts on an 8-second loop, with a crossfading "Breathe in / Breathe out" label — a literal visual representation of what the product does.
- **Structural devices:** feature list styled as ruled notebook lines (dashed dividers) rather than boxed cards; testimonials styled as slightly tilted index cards with a washi-tape accent; the "How it works" section uses numbered steps because it's a genuine 3-step sequence.

## Feature Checklist (per task requirements)

- [x] Sticky navigation bar with 3+ links (Features, How it works, Students say) plus a CTA
- [x] Hero section with headline, subheadline, and call-to-action button
- [x] 3 distinct content sections (Features, How it works, Testimonials) plus a final CTA section
- [x] Footer with placeholder contact/social links
- [x] Consistent colour palette applied across all sections
- [x] Responsive layout using CSS Grid + Flexbox — tested down to mobile widths, nav collapses, grids stack to 1 column
- [x] Deliberate spacing/padding — no element overlap
- [x] Clear typographic hierarchy (multiple font sizes/weights across headline, sub, body, labels)
- [x] `prefers-reduced-motion` respected for the hero animation

## Folder Structure (per OIBSIP guidelines)

```
OIBSIP/WebDev-L1-CalmDeskLandingPage/
├── index.html
└── README.md
```

## Notes

Built from scratch — layout, copy, and visual direction are original to this project (no template or existing site was copied). Visual inspiration was drawn only at a principles level from general landing-page design references, per the task's self-sourcing guideline.
