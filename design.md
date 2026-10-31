# Design

## Overview

A quiet, personal portfolio with a dark background, one restrained accent colour, and generous spacing. The visual hierarchy stays clear and the content remains easy to scan rather than adding decorative sections.

## Architecture

The Portfolio_Page is a single static HTML document. The document contains the header, project content, and footer in one page. Inline CSS controls the responsive layout and visual system. The page has no JavaScript, framework, build step, backend, or required external assets.

## Components and Interfaces

1. Header: name as the primary heading, followed by a concise role line.
2. Project content: four project cards in a responsive grid on wider screens and a single column on phones. Each card contains a title, one sentence, and one clear project link. The fourth card is titled `Demo project`, describes `demo-project from the conference`, and links to `https://example.com/demo-project`.
3. Footer: email, GitHub, and LinkedIn links, visually distinct from project links but using the same accent colour.

## Data Models

The page uses static HTML content rather than a runtime data model. Project cards contain owner-supplied titles, descriptions, and links.

## Visual system

- Dark neutral page background with high-contrast text.
- Use exactly one accent colour for links and small emphasis details.
- Generous page margins and vertical rhythm; cards use restrained borders or surface contrast to separate projects.
- Comfortable text measure and legible type sizes.
- At phone widths, stack content and keep links easy to tap; avoid horizontal scrolling.

## Implementation constraints

All markup and page content live in `index.html`; all styling lives in its `<style>` block. No JavaScript, framework, build step, backend, or required external assets.
