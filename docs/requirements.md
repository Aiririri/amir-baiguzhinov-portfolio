# Requirements baseline

**Project:** Amir Baiguzhinov — Personal Portfolio  
**Assignment:** TSIS #01 — Software Engineering  
**Status:** Draft baseline; requirements require owner/teacher review.

## 1. Purpose and audience
The website presents the student's education, interests, projects and professional identity. Primary audiences are course staff, classmates, prospective collaborators and visitors interested in the student's work.

## 2. Goals
- Present accurate, concise personal and educational information.
- Showcase projects and areas of experience.
- Provide a clear way to navigate and find professional links.
- Work on desktop and mobile.
- Support Kazakh, Russian and English with equivalent essential content.
- Be published through the hosting arrangement required by the assignment.

## 3. Scope
**In scope:** public personal portfolio, language switching, responsive layout, education, selected learning portfolio/coursework, interests, achievements and extracurricular activities where verified, future plans, projects, professional links, privacy notice, accessibility, testing and deployment.

**Out of scope:** user accounts, authentication, private dashboards, collection of visitor personal data, payment processing, a CMS, and reproducing Aruskin.ai functionality. Aruskin.ai is presented only as a project case study.

## 4. Constraints and assumptions
- The assignment requires Kazakh, Russian and English.
- Hosting must use InfinityFree and a free InfinityFree subdomain; HTTPS must be used.
- No paid hosting or domain purchase.
- Personal details are published only with the owner's consent.
- No private identifiers, home address, phone number, grades or personal documents.
- Content facts supplied so far: KBTU student since 2024 in Есептеу техникасы және бағдарламалық қамтамасыз ету (Computer Systems and Software); graduate of Nazarbayev Intellectual School, Physics and Mathematics direction, Ust-Kamenogorsk; Founder & CEO of Aruskin.ai; language levels and interests are listed on the website.
- The programme name was supplied by the owner in Kazakh and English. Completed subjects, achievements, extracurricular activities and future plans have not yet been confirmed.

## 5. Functional requirements
| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The home section shall introduce the owner and identify the site as a personal portfolio. | Must |
| FR-02 | The site shall present KBTU education and previous high-school education accurately. | Must |
| FR-03 | The site shall present projects with safe, working external links. | Must |
| FR-04 | The site shall present interests and language proficiency supplied by the owner. | Must |
| FR-05 | The site shall provide clear navigation to all major sections. | Must |
| FR-06 | The site shall allow visitors to switch between Kazakh, Russian and English from the main page. | Must |
| FR-07 | The site shall present selected completed subjects/learning portfolio with accurate descriptions. | Should |
| FR-08 | The site shall present achievements, extracurricular activities and future plans when verified by the owner. | Should |
| FR-09 | The site shall provide professional/contact links without exposing unnecessary personal data. | Must |
| FR-10 | The site shall display a short privacy statement. | Must |

## 6. Non-functional requirements
| ID | Requirement | Priority |
|---|---|---|
| NFR-01 | Responsive: content and navigation shall remain usable on common mobile and desktop viewport sizes. | Must |
| NFR-02 | Usability: section labels, navigation and links shall be clear and consistent. | Must |
| NFR-03 | Accessibility: semantic structure, keyboard access, visible focus, meaningful labels and reduced-motion accommodation shall be provided. | Must |
| NFR-04 | Privacy: only owner-approved public information shall be displayed; no private identifiers or secrets. | Must |
| NFR-05 | Security: deployment shall use HTTPS; no credentials or secrets shall be stored in the public repository. | Must |
| NFR-06 | Performance: avoid unnecessary scripts, packages and large assets; keep the page lightweight. | Should |
| NFR-07 | Maintainability: readable HTML/CSS/JS, documented structure and meaningful commits. | Must |
| NFR-08 | Compatibility: core content and navigation shall work in current major desktop and mobile browsers. | Must |
| NFR-09 | Reliability: essential links and assets shall load without errors on the deployed site. | Must |
| NFR-10 | Internationalization: all essential content and interface text shall be complete and consistent in three required languages. | Must |

## 7. User stories and acceptance criteria
### US-01 — Understand who the owner is
**Given** I am a first-time visitor, **when** I open the home section, **then** I can identify the owner and understand the site's purpose.

### US-02 — Review education
**Given** I am interested in the owner's background, **when** I open Education, **then** I can find KBTU and previous high-school information without unsupported claims.

### US-03 — Explore a project
**Given** I want to see the owner's work, **when** I open Projects and follow the Aruskin.ai link, **then** the project opens in a separate tab and the portfolio remains available.

### US-04 — Navigate on a phone
**Given** I visit on a mobile viewport, **when** I use the navigation, **then** I can open each main section using keyboard or touch without horizontal overflow.

### US-05 — Change language
**Given** I am viewing the site in one supported language, **when** I choose another language, **then** the page content, navigation, controls and metadata change consistently and I remain oriented in the same section.

### US-06 — Protect personal information
**Given** I review the public site, **when** I inspect its content and links, **then** I do not find private identifiers, home address, phone number, grades, private documents or unapproved information about other people.

### US-07 — Find professional links
**Given** I want to contact or learn more about the owner, **when** I open Contact, **then** I can access the published GitHub profile and project link without needing private contact data.

### US-08 — Read the site accessibly
**Given** I use keyboard navigation or assistive technology, **when** I move through the page, **then** landmarks, headings, links and controls have meaningful names and visible focus.

## 8. Current baseline gaps
- Current website content is English-only; FR-06 and NFR-10 are not implemented.
- The language selector is not present.
- Completed subjects/learning portfolio, achievements, extracurricular activities and future plans need owner-provided facts.
- A privacy statement needs to be added.
- Hosting, HTTPS, manual testing and launch evidence are not yet completed.
- No executed test results are claimed in this repository at this stage.
