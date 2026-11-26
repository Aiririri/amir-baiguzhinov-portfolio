# Product backlog and iteration plan

**Status:** Planned work. Iteration completion must be updated only after implementation and evidence.

## Prioritized backlog

| ID | Item | Priority | Estimate | Depends on |
|---|---|---:|---:|---|
| PB-01 | Confirm personal content gaps with owner (major name, coursework, achievements, extracurriculars, future plans). | P0 | S | Owner input |
| PB-02 | Add Kazakh/Russian/English language selector and equivalent page content. | P0 | L | PB-01 |
| PB-03 | Add complete privacy statement and review published content. | P0 | S | PB-01 |
| PB-04 | Add selected coursework/learning portfolio section using verified facts. | P1 | M | PB-01 |
| PB-05 | Add achievements, extracurriculars and future plans if owner supplies facts. | P1 | M | PB-01 |
| PB-06 | Complete sitemap, use-case and component diagrams. | P0 | S | Requirements |
| PB-07 | Execute responsive, navigation, accessibility and link tests. | P0 | M | PB-02 |
| PB-08 | Conduct manual user test with at least one other person; record defects and retests. | P0 | M | PB-07 |
| PB-09 | Perform agentic code review and verify findings. | P1 | M | Stable implementation |
| PB-10 | Deploy to InfinityFree free subdomain with HTTPS. | P0 | M | PB-02, PB-07 |
| PB-11 | Verify public launch, capture screenshots and record final commit. | P0 | S | PB-10 |
| PB-12 | Prepare report, AI evidence, demo text and presentation. | P0 | L | PB-08–PB-11 |

## Iteration 1 — Baseline and design
**Goal:** establish a traceable engineering baseline before extending the website.

- [x] Record project scope and initial requirements baseline.
- [x] Create initial backlog.
- [x] Add repository instructions.
- [x] Add initial design and test documentation.
- [ ] Confirm content gaps with the owner.
- [ ] Confirm requirements with teacher/checkpoint #01.
- [ ] Review sitemap and diagrams with teacher/checkpoint #02.

## Iteration 2 — Implementation, quality and launch
**Goal:** complete required features, verify quality and publish the release.

- [ ] Implement three complete languages and language switching.
- [ ] Add verified coursework, future plans, achievements and extracurriculars.
- [ ] Add privacy statement and complete metadata translations.
- [ ] Execute at least 12 tests and update traceability.
- [ ] Conduct external manual user testing and fix verified defects.
- [ ] Complete AI review evidence and evaluation of suggestions.
- [ ] Deploy to InfinityFree and verify HTTPS public URL.
- [ ] Prepare final report, AI evidence, demo file and presentation.

## Change log by checkpoint
| Checkpoint | Expected review | Status |
|---|---|---|
| #01 | Scope, public/private content, stories, criteria and backlog | Not yet reviewed |
| #02 | Sitemap, wireframes, UML, architecture and multilingual plan | Draft documentation created; review pending |
| #03 | First deployed/local version, repository structure and risks | Local/source version exists; formal review pending |
| #04 | Traceability, executed tests, defects, agent review and corrections | Pending |
| #05 | Public URL, final evidence, reflection and demonstration | Pending |
