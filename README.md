# RE:FIT Dashboard

A responsive recreation of the supplied 1920 × 1200 RE:FIT dashboard design, built with React 19, Vite 6, Tailwind CSS 4, and Lucide icons.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

The app uses reusable React components, local Inter font files, the original embedded reference imagery, and SVG charts / dot-matrix numerals. No API keys are required.

## Interactive demo

- Complete workouts with checkboxes; state persists on this device.
- Toggle daily check-ins, browse months, and inspect the monthly total.
- Switch activity days and weeks.
- Cancel scheduled classes with confirmation.
- Search the workout list and change the header date range.
- Open notifications, fitness details, insights, wearable details, and the coach preview.
- Toggle light and dark mode.
- Add progress records; entries persist on this device.
- Use Settings → Reset demo to restore the starting state.

This is a frontend prototype. Fitness values are sample data; live wearable syncing and live coach video are not connected. The date range selector stores the chosen range but does not fetch new data. The sidebar opens related dashboard detail views.

## Project structure

- `src/main.jsx` — React components and demo state
- `src/styles.css` — Tailwind CSS import, reference design tokens, component styles, and responsive breakpoints
- `public/assets/` — optimized images and vector brand artwork extracted from the supplied SVG
