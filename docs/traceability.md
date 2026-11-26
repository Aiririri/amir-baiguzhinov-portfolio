# Requirements traceability matrix

**Status:** planned test mapping. Results remain **Not run** until tests are actually executed.

| Requirement / story | Planned verification | Test ID | Current result |
|---|---|---|---|
| FR-01 / US-01 | Verify introduction and site identity are visible. | TC-01 | Not run |
| FR-02 / US-02 | Verify KBTU and previous school details match owner-approved facts. | TC-02 | Not run |
| FR-03 / US-03 | Open Aruskin.ai link; verify destination and separate-tab behavior. | TC-03 | Not run |
| FR-04 | Verify interests and language levels match supplied facts. | TC-04 | Not run |
| FR-05 / US-04 | Navigate all sections on desktop and mobile. | TC-05 | Not run |
| FR-06 / US-05 | Switch between Kazakh, Russian and English; verify equivalent content and page language. | TC-06 | Blocked — language feature not implemented |
| FR-07 | Verify selected coursework/learning portfolio descriptions against owner-approved list. | TC-07 | Blocked — content not supplied |
| FR-08 | Verify achievements, extracurriculars and future plans against owner-approved facts. | TC-08 | Blocked — content not supplied |
| FR-09 / US-07 | Verify professional links and absence of unnecessary personal contact details. | TC-09 | Not run |
| FR-10 / US-06 | Verify privacy statement appears and accurately describes data handling. | TC-10 | Blocked — not yet on website |
| NFR-01 | Check narrow mobile, tablet and desktop viewport layouts; detect horizontal overflow. | TC-11 | Not run |
| NFR-03 / US-08 | Keyboard-only navigation, focus visibility, semantic landmarks and accessible names. | TC-12 | Not run |
| NFR-05 | Verify deployed site redirects/loads over HTTPS and repository contains no secrets. | TC-13 | Blocked — deployment pending |
| NFR-08 | Check current Chrome, Firefox, Safari and mobile browser where available. | TC-14 | Not run |
| NFR-09 | Check essential links/assets on public deployed site. | TC-15 | Blocked — deployment pending |
| NFR-10 | Review all essential content, navigation, controls and metadata in all three languages. | TC-16 | Blocked — language feature not implemented |

## Result policy
- Use **Pass** only after executing the stated test and recording evidence.
- Use **Fail** when the executed test reveals a defect.
- Use **Blocked** when a prerequisite is missing.
- Use **Not run** when the test has not been executed.
- After a fix, record the retest result and link the relevant commit or screenshot.
