# Jack -- 3D Creator Portfolio

A dark-themed 3D creator portfolio landing page built with React, TypeScript, Tailwind CSS, and Framer Motion.

## Setup

```bash
npm install
npm run dev
```

Then open the printed local URL in your browser.

## Build

```bash
npm run build
npm run preview
```

## Structure

- `src/App.tsx` -- assembles the five sections in order: Hero, Marquee, About, Services, Projects.
- `src/components/HeroSection.tsx` -- full-viewport intro with navbar, gradient headline, magnetic portrait image, and contact CTA.
- `src/components/MarqueeSection.tsx` -- two scroll-driven rows of GIF tiles moving in opposite directions.
- `src/components/AboutSection.tsx` -- centered bio with decorative corner images and a character-reveal paragraph.
- `src/components/ServicesSection.tsx` -- light-themed numbered list of five services.
- `src/components/ProjectsSection.tsx` -- three sticky, scale-stacking project cards.
- `src/components/FadeIn.tsx`, `Magnet.tsx`, `AnimatedText.tsx`, `ContactButton.tsx`, `LiveProjectButton.tsx` -- shared, reusable building blocks used across sections.

All images are loaded from the external URLs specified in the design brief; an internet connection is required to see them render.
