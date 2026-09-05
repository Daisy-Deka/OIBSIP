# Daisy Deka — Personal Portfolio (OIBSIP Web Dev, Level 1, Task 2)

A single-page personal portfolio built as my digital résumé — profile, background, skills, and real project work, all in one place.

## Live Preview

Open `index.html` directly in any browser — no build step, no dependencies beyond a Google Fonts link.

## Tech Stack

- HTML5
- CSS3 (Flexbox + Grid)
- A small amount of vanilla JavaScript (optional enhancement only — highlights the active nav link while scrolling via `IntersectionObserver`; the page works fully without it)
- Google Fonts: Fraunces (display) + IBM Plex Sans (body)

## Design Concept

Since most of my project work sits at the intersection of AI/ML and healthcare, the visual direction leans into that world without being literal about it:

- **Palette:** clinical paper background, deep teal-charcoal ink, a single coral-red accent reserved for one signature moment and link hovers.
- **Signature element:** a pulse/ECG line that draws itself once behind the avatar on page load — a single deliberate animation rather than scattered hover effects.
- **Typography:** Fraunces (a distinctive serif) for my name and headings, paired with IBM Plex Sans for body text — two clearly distinct families, no monospace data labels.
- **Structure:** an "at-a-glance" stat panel next to the About text (CGPA, graduation year, certifications) and project cards with a simple top-accent instead of the generic rounded-card-with-shadow treatment.

## Feature Checklist (per task requirements)

- [x] Profile/hero section: name, role title, and an avatar placeholder (initials, since no photo was supplied)
- [x] About Me section: background and interests, in first person
- [x] Skills section: categorized visual grid (Languages, ML & Data, Mobile & Cloud, Tools)
- [x] Projects section: 5 real project cards (title, description, tech tags, GitHub link placeholder)
- [x] Contact section: name, email, GitHub and LinkedIn links
- [x] Smooth scroll navigation between sections (native CSS `scroll-behavior: smooth`)
- [x] Consistent branding (colour scheme and font family) throughout
- [x] Fully responsive — nav, hero, skills grid, and project grid all reflow for mobile widths

## Before you consider this final

A few placeholders need to be swapped for the real thing:
- **Email:** currently `daisy.deka@example.com` — replace with your actual email in both the hero and contact section
- **LinkedIn link:** currently a `#` placeholder — replace with your actual profile URL
- **Project GitHub links:** currently `#` placeholders — replace each with the actual repo URL once pushed

## Folder Structure (per OIBSIP guidelines)

```
OIBSIP/WebDev-L1-PersonalPortfolio/
├── index.html
└── README.md
```

## Notes

Built from scratch — layout, copy, and visual direction are original to this project (no template or existing portfolio was copied). Visual inspiration was drawn only at a principles level, per the task's self-sourcing guideline.
