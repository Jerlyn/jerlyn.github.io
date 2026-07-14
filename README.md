# jerlyn.github.io

Portfolio homepage for Jerlyn O'Donnell — Experience Design Director, Author, Illustrator, and Founder of [Design Lady LLC](https://designlady.com).

Built to the same standard I hold client work to: accessibility in from day one, not retrofitted.

---

## Accessibility & Compliance Log

| Component | Status | WCAG Criterion | Notes |
| :--- | :--- | :--- | :--- |
| Color Contrast — Body Text | Pass | 1.4.3 | Minimum 5.8:1 in light mode (#545C6B on #F8F9FA). Dark mode muted text ~5.2:1. |
| Color Contrast — Accent (Teal) | Pass | 1.4.3 | Dark mode #4ADEDE; light mode overridden to #0A6B6B (5.9:1). |
| Color Contrast — Accent (Pink) | Pass | 1.4.3 | Dark mode #DE6399 on large text only (3.3:1 passes large-text threshold); light mode overridden to #A01C5A (7.5:1). |
| Color Contrast — Hero Text | Pass | 1.4.3 | White text over brand gradient + dark veil. Worst-case white video frame yields 7:1+ at text zone. |
| Keyboard Navigation | Pass | 2.1.1 | All interactive elements operable via keyboard. |
| Focus Indicators | Pass | 2.4.7 | Custom `:focus-visible` using brand purple (#36069A) with white halo; teal (#4ADEDE) variant on dark backgrounds. |
| Video Autoplay — Pause Control | Pass | 2.2.2 | Hero background video has visible Pause/Play toggle. |
| Reduced Motion | Pass | 2.2.2 / 2.3.3 | `prefers-reduced-motion: reduce` pauses video and disables scroll/marquee animations. |
| Semantic Structure | Pass | 1.3.1 | Proper heading hierarchy (H1 → section labels). ARIA landmarks on nav, sections, footer. |
| Link Purpose | Pass | 2.4.4 | All vibe code cards and project links have descriptive `aria-label` attributes. Visible "View →" text supplemented by full project name in accessible label. |
| Image Alt Text | Pass | 1.1.1 | All `<img>` elements carry descriptive alt text. Decorative duplicates in logo marquee use `alt=""`. |
| Logo Marquee — Motion | Pass | 2.2.2 | Marquee pauses on hover and on `prefers-reduced-motion`. Full client list provided in `aria-label` on the wrapper for screen readers. |
| Font Weight in Light Mode | Pass | 1.4.3 | `font-weight: 300` overridden to 400 in light mode on all body-sized prose elements. |

*Last audit: July 2026*
*Auditor: Jerlyn O'Donnell, CPACC*

---

## Tech Stack

- Vanilla HTML/CSS/JS — no framework dependencies
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) (display) + [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (body) via Google Fonts
- Images served from existing CDN endpoints (Webflow, GitHub Pages)
- No build step required

## Related

- [designlady.com](https://designlady.com) — full portfolio and case studies
- [jerlyn.github.io/vibecode](https://jerlyn.github.io/vibecode) — vibe code project gallery
- [@commuteartist](https://instagram.com/commuteartist) — illustration practice
