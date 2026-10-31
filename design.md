# Design

## Direction
A quiet, personal portfolio with a dark background, one restrained accent colour, and generous spacing. Keep the visual hierarchy clear and the content easy to scan rather than adding decorative sections.

## Structure
1. Header: name as the primary heading, followed by a concise role line.
2. Main content: three project cards in a responsive grid on wider screens and a single column on phones. Each card contains a title, one sentence, and one clear project link.
3. Footer: email, GitHub, and LinkedIn links, visually distinct from project links but using the same accent colour.

## Visual system
- Dark neutral page background with high-contrast text.
- Use exactly one accent colour for links and small emphasis details.
- Generous page margins and vertical rhythm; cards use restrained borders or surface contrast to separate projects.
- Comfortable text measure and legible type sizes.
- At phone widths, stack content and keep links easy to tap; avoid horizontal scrolling.

## Implementation constraints
All markup and page content live in `index.html`; all styling lives in its `<style>` block. No JavaScript, framework, build step, backend, or required external assets.