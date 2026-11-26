# Test plan

## Scope
Test the personal portfolio's content, navigation, language support, responsive behavior, accessibility, links, browser compatibility, security hygiene and deployed version.

## Test environment to record
For each execution, record:
- Date and tester
- Device and operating system
- Browser and version
- Viewport dimensions
- Commit identifier or deployed URL
- Steps, expected result, actual result and evidence reference

## Planned test cases
| ID | Area | Steps | Expected result |
|---|---|---|---|
| TC-01 | Home | Open the home page. | Name, introduction and portfolio purpose are clear. |
| TC-02 | Education | Navigate to Education. | KBTU and previous school facts are accurate and readable. |
| TC-03 | Project link | Activate the Aruskin.ai link. | Correct external site opens; portfolio remains available. |
| TC-04 | Content | Review interests and languages. | Content matches owner-approved information. |
| TC-05 | Navigation | Open each navigation link on desktop and mobile. | Each link reaches the intended section; mobile menu closes after selection. |
| TC-06 | Language | Select KZ, RU and EN; refresh the page after each selection. | Translated page content, navigation, metadata and active-button state update; selected language persists after refresh. |
| TC-07 | Coursework | Review learning portfolio section. | Only verified completed subjects and descriptions are shown. |
| TC-08 | Personal content | Review achievements, extracurriculars and future plans. | Only owner-confirmed details are published. |
| TC-09 | Contact | Open each professional link. | Links work and no unnecessary private contact information is exposed. |
| TC-10 | Privacy | Review privacy statement. | Statement is visible and matches actual site behavior. |
| TC-11 | Responsive | Check 360px, 768px and 1440px widths. | No unintended horizontal overflow; text and controls remain usable. |
| TC-12 | Accessibility | Use keyboard only; inspect landmarks, headings and focus. | Navigation and links are keyboard accessible and have meaningful names. |
| TC-13 | HTTPS/security | Open deployed URL with HTTPS; inspect repository for secrets. | Public site uses HTTPS; no secrets are committed. |
| TC-14 | Browser compatibility | Repeat core navigation/content checks in available browsers. | Core content and navigation work consistently. |
| TC-15 | Deployed links/assets | Open every essential link and asset on hosted site. | No broken essential links or missing assets. |
| TC-16 | Internationalization | Compare all three language versions and metadata. | Content is complete, consistent and correctly tagged in each language. |

## Manual user testing
At least one person other than the owner should complete a short task set:
1. Find the owner's education.
2. Open the featured project.
3. Find the language selector and change language.
4. Navigate the site on a phone-sized viewport.
5. Find the professional links.

Ask the tester to report confusing labels, missing information and navigation problems. Record tester consent without collecting unnecessary personal information. Do not invent a tester, feedback or results.

## Automated checks
Use automated HTML validation and link checking where available. Record the exact tool, version, command, date and output. Automated checks supplement, but do not replace, manual keyboard, responsive and user testing.

## Execution status
No test execution results are recorded yet. Use `test-log.md` to document actual outcomes.
