# Project Brief

Personal website. Homepage + separate case study pages.

## Tech
- Plain HTML + CSS. No frameworks, no build tools.
- Font: Denim WD (custom, self-hosted via @font-face from /assets/fonts/)
- Responsive
- Dark mode: follows system preference (prefers-color-scheme) + manual toggle
- Use Radix color tokens for theming (to be configured)

## Pages
- index.html (homepage)
- pages/duffel.html (case study - long editorial scroll)
- pages/ferriswheel.html (case study - TBD)
- pages/ee.html (case study - TBD)

## Homepage sections
1. Hero - name (English + Arabic), title
2. Duffel card - logo, description, tags, screenshots, links to case study
3. Ferriswheel card - same pattern
4. EE card - same pattern
5. Testimonials - three quotes
6. About - bio + avatar
7. Footer

## Dark mode notes
- Duffel section: swap image assets + iframe embeds to dark variants
- Other sections: same assets, just site chrome changes

## Assets
- Images in /assets/img/
- Font files in /assets/fonts/
- HTML embeds in /assets/embeds/ (iframes, full-width)
- Video in /assets/video/ (looping, muted, autoplay)

## Working style
- Build section by section. I'll share Figma screenshots.
- Don't generate placeholder text. Ask me if copy is missing.
