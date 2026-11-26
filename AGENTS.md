# Repository instructions

## Project scope
This repository contains Amir Baiguzhinov's personal portfolio website for TSIS #01 (Software Engineering). It is separate from Aruskin.ai.

## Structure
- `index.html` — semantic single-page portfolio content and navigation
- `style.css` — visual design, responsive layouts, focus and reduced-motion styles
- `script.js` — small progressive-enhancement interactions
- `docs/` — requirements, backlog, ethics, design, testing and traceability
- `diagrams/` — editable Mermaid diagram source
- `tests/` — manual test cases and execution log template

## Conventions
- Use semantic HTML5 and UTF-8.
- Keep dependencies minimal; prefer vanilla HTML, CSS and JavaScript.
- Keep content truthful. Do not invent courses, grades, awards, employment history, extracurricular activities, contact details or technical skills.
- Do not publish private identifiers, home address, phone number, grades or personal documents.
- Preserve the minimalist visual direction and responsive behavior.
- All essential content, navigation, buttons and metadata must be available in Kazakh, Russian and English before release.
- Use accessible labels, keyboard operation, visible focus and reduced-motion support.
- Never commit passwords, API keys, hosting credentials or other secrets.

## Local run
Open `index.html` in a browser, or run `python -m http.server 8000` and visit `http://localhost:8000`.

## Acceptance criteria
See `docs/requirements.md` and `docs/traceability.md`. A requirement is not complete merely because it is documented. Record actual implementation and test evidence before marking it passed.

## Change workflow
1. Read relevant requirements and acceptance criteria.
2. Make a focused change.
3. Inspect the diff and check for fabricated content, broken links, accessibility regressions and responsive issues.
4. Execute applicable tests and record actual results in `tests/test-log.md`.
5. Update traceability and documentation to match the verified state.

## Release constraints
The TSIS brief requires InfinityFree hosting with a free InfinityFree subdomain and HTTPS. Do not claim deployment until the public URL has been opened and checked. Preserve the final Git commit identifier and launch evidence.
