# FTNZ Examiner Recurrent Programme — Source and Review Map

## Source set reviewed

- `FW_ Examiner Periodic Refresher PD Course - Updated..eml` — Steve Kingsbury’s request for an FTNZ LMS portal, staged block availability, approximately 50 examiners, participant name and CAA participation ID capture, and a completion record rather than a certificate.
- `Infographic_Development_Brief_Examiner_Refresher.docx` — seven instructional visual concepts, accessible text requirements and restrained FTNZ aviation-professional treatment.
- `Design_and_Implementation_FTNZ Examiner_Refresher.docx` — three-block, six-year recurrent architecture; self-paced delivery; calibration method; completion/records; scope and governance.
- `Blocks 1-3_Examiner_Refresher_Course.docx` — learner-facing Block 1, Block 2 and Block 3 lessons, scenarios, decision points, model reasoning, reflections and answer keys.
- `FTNZ_Logo_HiRes_Transparent.png` and `FTNZ_Logo_HiRes_White.png` — supplied brand assets; the transparent version is used on the light course welcomes and tenant header.

## Course mapping

| Source block | Course entry | Module | Core content |
| --- | --- | --- | --- |
| Block 1 | `aviation-examiner-recurrent-block-1` | `ftnz-examiner-block-1-professional-judgement` | 7 content lessons plus knowledge check, 16 objective questions, staged mixed-evidence workshop; optional field aid |
| Block 2 | `aviation-examiner-recurrent-block-2` | `ftnz-examiner-block-2-readiness-human-performance` | 6 content lessons plus knowledge check, 13 objective questions, staged assessment-changes workshop; optional field aid |
| Block 3 | `aviation-examiner-recurrent-block-3` | `ftnz-examiner-block-3-identity-communication-evidence` | 6 content lessons plus knowledge check, 15 objective questions, staged difficult-debrief workshop; optional field aid |

## Visual mapping

- Infographic 1 — recurrent calibration question: Block 1 Lesson 1.1 and Block 3 Lesson 3.6.
- Infographic 2 — examiner drift: Block 1 Lesson 1.2.
- Infographic 3 — isolated error or emerging pattern: Block 1 Lesson 1.3, placed after the scenario explanation so it does not give away the decision.
- Infographic 4 — behaviour to assessment decision: Block 2 Lesson 2.3, placed after the scenario explanation.
- Infographic 5 — recovery as part of the evidence story: Block 2 Lesson 2.4, placed after the scenario explanation.
- Infographic 6 — evidence vs interpretation vs conclusion: Block 3 Lesson 3.4.
- Infographic 7 — communication without coaching: Block 3 Lesson 3.2, placed after the scenario explanation.
- Raster contextual scenes: live assessment in Block 1, readiness/weather in Block 2, and professional debriefing in Block 3.
- Each core SVG infographic now has a high-resolution PNG delivery asset beside the editable SVG source.

## Deliberate normalisations and open approvals

- The source appendices contain lesson-number drift (`2.7`/`3.7`) and answer-key labels that do not match the lesson maps. The package uses stable lesson order and a final knowledge-check lesson per block.
- The generic calibration cases do not include a particular approved FTNZ competency or assessment criterion. They are labelled reasoning practice and do not invent a pass/fail outcome.
- The course manifests no longer assert a course-level 80% threshold. The quiz files retain a compatibility `passingScore: 80` field because the bundled structural validator requires it, but the current player ignores that quiz-level field and still has an 80% fallback. The supplied design describes formative self-checks and says any formal assessment requirement must be separately specified by FTNZ; a platform-level formative-quiz mode remains required before operational release if FTNZ does not approve a pass mark.
- Course completion is set to `enforce` so the learner must meet the player’s reading/engagement evidence before continuing. Structured reflections still remain private browser-local inputs and are not yet server-backed completion evidence; that requires a platform completion-activity integration.
- The requested participant name/CAA participation ID completion record is not implemented by course files. It requires a server-backed participant-record field, admin reporting/export, and FTNZ approval of retention/access rules. The course text does not pretend that browser-local reflections are that record.
- Block availability is represented as three separate course entries so FTNZ can assign one block at a time. The live tenant must still maintain the intended cohort/course access rows before operational delivery.
