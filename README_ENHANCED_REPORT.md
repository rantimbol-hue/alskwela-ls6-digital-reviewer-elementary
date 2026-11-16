# ALSKwela A&E 2027 — Enhanced PDF Report v2

This patch updates only the learner-generated PDF and the printable study report, without modifying the original questions, answer choices, answer keys, feedback, curriculum mappings, app names, or saved-progress keys.

## Updated report content

1. A clear personalized score overview and performance bars by learning domain.
2. Prioritized study topics selected from missed questions' original learning competency IDs and review-focus fields.
3. All missed questions FIRST, including the original situation, selected option, correct option, existing professional Taglish explanation, and curriculum-linked review topic.
4. Correct responses SECOND, with optional brief explanations (controlled by the checkbox).
5. A printable personal study checklist ordered by missed-competency frequency.
6. A teacher-verifiable item ID, selected answer, correct answer, score, trial date, and learner name.

Note: The source bank has a correct-answer explanation, but not a separate validated rationale for every distractor. This report will not invent one. The review topic is a recommendation based on performance in this single trial, not a verified diagnosis of mastery.

## Deploy an update to an existing GitHub Pages repository

1. Back up the existing repository. Ask current learners to complete or export unfinished practice trials before the update.
2. Extract ONLY the ZIP for the matching level and learning strand.
3. Upload the extracted files (especially index.html and sw.js) to the ROOT of that existing repository, replacing files of the same names; keep the published branch and path unchanged.
4. Commit. In GitHub Settings > Pages, check that the updated deployment succeeds.
5. Open the existing link in Android Chrome while online; refresh and reopen the installed reviewer. Service-worker cache identifiers were updated so the enhanced PDF code is cached.
6. Run a new practice trial. Download the enhanced PDF and use Print / Save as PDF for a print-friendly visual version. Repeat in airplane mode.

The GitHub Pages URL, the PWA manifest id and app name, and local saved-progress keys remain unchanged.
Each PWA stores data locally. Reports are not automatically sent to a teacher or uploaded to a server.

## Verification recommendations

- Test one correct and one incorrect answer, then inspect their ordering in the report.
- Confirm the recommended LC IDs refer to the learner's incorrect answers.
- Check all original questions and shuffled answer letters are present and correct.
- Check PDF works in airplane mode and opens in the phone's PDF viewer.
- Always subject-matter review draft A&E questions before official use.
