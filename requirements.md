# Requirements Document

## Introduction

Create a one-page personal portfolio as a single static `index.html` file.

## Glossary

- **Portfolio_Page**: The single-page personal portfolio delivered in `index.html`.
- **Owner**: The person supplying personal details, project information, and link destinations.

## Requirements

### Required content

- Personal name and one-line role in the header.
- Four projects, each with a title, one-sentence description, and one link.
- The fourth project is titled `Demo project`, described as `demo-project from the conference`, and linked to `https://example.com/demo-project`.
- Footer links for email, GitHub, and LinkedIn.
- Personal details and project information must be supplied by the Owner; the Portfolio_Page must not invent them.

### Technical constraints

- Put all CSS in an inline `<style>` block in `index.html`.
- No framework, build step, backend, or JavaScript.
- Write page content directly in the HTML.
- The Portfolio_Page must be usable on phones and desktop browsers.
- Deliver the requested planning documents before implementation and wait for approval before building.

### Acceptance criteria

- A single `index.html` contains the complete page and styles.
- All required content and links are present, with working destinations supplied by the Owner.
- Layout adapts to narrow screens without horizontal overflow or unreadable text.
- No scripts, external frameworks, or build tooling are required.
