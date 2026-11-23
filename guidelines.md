# Versions of Eylosh — Design Guidelines

These rules apply to every change. Read them before editing anything.

## Identity
- Personal portfolio of Eylem Eylül Acarsoy ("Eylosh"), an interdisciplinary designer and design researcher.
- Tone: warm, witty, a little mischievous, but always professional where the work is described. Humour lives in the margins (loading, hovers, footer, empty states), never in project descriptions.
- Copy is lowercase in playful/system UI (intro, lens buttons, status lines). Project titles and project text keep normal capitalisation.
- Never invent projects, roles, dates or skills. Anything marked PLACEHOLDER stays visibly marked as a placeholder.

## Typography
- One family: JetBrains Mono (Google Fonts), weights 300, 400, 700, 800. Fallback: ui-monospace, Menlo, monospace.
- Big, bold headlines (800). Body 400. System/status lines 300–400 at small sizes.
- Generous line-height (1.5–1.7) for body text.

## Colour
- Paper: #FFFFFF. Ink: #000000. Accent: neon green #0DFF00 (adjust with Eylül).
- Green has two jobs: (1) "now" — the current period in the My Story timeline, as in the 2026 portfolio; (2) state — active lenses, intersections, hovered items, links. Never a large background behind body text.
- The My Story timeline is a fixed brand element: solid black blocks, white text, green for the present. Do not restyle it.
- Project covers: full-bleed photo with a dark overlay, title and question in green on top (same as her 2026 PDF).
- No gradients, no glassmorphism, no drop shadows.

## ASCII as a design language
- Use block characters ▒ ▓ █ ░ ▄ ▀ as dividers, progress bars, intersection markers and loading states. They carry information (counts, progress, state), they are not random decoration.
- ASCII cats (/\\_/\\ ( o.o ) > ^ <) may appear in exactly one or two places.

## Logo
- Circle with radiating bars (Eylül will upload the SVG). Until then use a placeholder circle labelled PLACEHOLDER LOGO.
- The logo is the lens dial: its bars can light up to reflect the selected lenses.

## Interaction principles
- Every interaction must do something meaningful: filter, reveal, explain, navigate. No buttons that do nothing.
- Hover reveals detail; click commits. Motion: short (150–300ms), ease-out, no bouncing.
- Respect prefers-reduced-motion: disable typing and scroll animations.
- The loading/intro sequence must be skippable and never block access to work or CV.

## Layout
- Strong whitespace, editorial grids, unexpected but readable compositions. Sections should not all look identical.
- Fully responsive. On mobile the timeline scrolls horizontally with touch; lens buttons wrap.

## Data
- All content comes from content.json and index.json. Do not hard-code project text in components. Adding a project = adding an object to the JSON.
