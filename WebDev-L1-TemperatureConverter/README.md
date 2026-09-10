# Temperature Converter (OIBSIP Web Dev, Level 1, Task 3)

An interactive tool that converts a temperature between Celsius, Fahrenheit, and Kelvin, with real-time input validation and absolute-zero checking.

## Live Preview

Open `index.html` in any browser — no build step, no dependencies beyond a Google Fonts link.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks)
- Google Fonts: Space Grotesk (UI text) + JetBrains Mono (numeric readouts)

## Why it looks the way it does

I wanted this one to feel like an actual instrument rather than a form on a page, since it's a measurement tool, not a marketing page. It's a dark panel with a subtle blueprint-grid texture behind it, an amber glowing readout styled like a gauge display, and a glass-tube thermometer with tick marks next to the main readout — it actually fills and shifts colour (blue for cold, amber for moderate, red for hot) based on the last converted value, with a soft glow that matches. When you hit Convert, the numbers count up smoothly instead of just snapping into place. All of it is tied to the actual function of the tool rather than being decoration for its own sake.

## How it works

- Type a number into the input field. It validates as you type — non-numeric input shows an error immediately.
- Pick which unit that number is in (Celsius, Fahrenheit, or Kelvin).
- Click Convert (or press Enter). All three unit tiles update at once, so you see the value in all three units simultaneously, not just the one you didn't pick.
- If the converted value comes out below absolute zero (−273.15°C / −459.67°F / 0 K), it shows a clear error instead of a nonsense negative-Kelvin number. Absolute zero itself is treated as valid, in whichever unit it's entered.

## Feature Checklist (per task requirements)

- [x] Numeric input field with real-time validation, rejects non-numeric input with an error message
- [x] Unit selector (Celsius / Fahrenheit / Kelvin) for the input value
- [x] Auto-conversion showing all three output units simultaneously
- [x] Convert button that triggers the calculation
- [x] Result display area with correct unit labels for each value
- [x] Edge case handling for absolute zero violations, with a friendly message
- [x] Clean, centred UI layout with clear labels

## Folder Structure (per OIBSIP guidelines)

```
OIBSIP/WebDev-L1-TemperatureConverter/
├── index.html
└── README.md
```

## Notes

Built from scratch — the conversion logic, layout, and visual direction are all mine. I checked the standard conversion formulas and MDN's input validation guidance per the task's self-sourcing guideline, but didn't copy any existing converter tool or template.
