# FTNZ Examiner Recurrent Programme — Source and Review Map

## Source set reviewed

- `FW_ Examiner Periodic Refresher PD Course - Updated..eml` — Steve Kingsbury’s request for an FTNZ LMS portal, staged block availability, approximately 50 examiners, participant name and CAA participation ID capture, and a completion record rather than a certificate.
- `Infographic_Development_Brief_Examiner_Refresher.docx` — seven instructional visual concepts, accessible text requirements and restrained FTNZ aviation-professional treatment.
- `Design_and_Implementation_FTNZ Examiner_Refresher.docx` — three-block, six-year recurrent architecture; self-paced delivery; calibration method; completion/records; scope and governance.
- `Blocks 1-3_Examiner_Refresher_Course.docx` — learner-facing Block 1, Block 2 and Block 3 lessons, scenarios, decision points, model reasoning, reflections and answer keys.
- `FTNZ_Logo_HiRes_Transparent.png` and `FTNZ_Logo_HiRes_White.png` — supplied brand assets; the transparent version is used on the light course welcomes and tenant header.
- `Block 1 corrections.docx` — FTNZ review instructions for terminology, pacing, mandatory responses, infographic layout, reveal controls, quiz design, attempt limits and the completion-record workflow.

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
- The final five-question review sets are now visible inside each review lesson as source-matched self-checks with model reasoning; they remain duplicated in the knowledge-check files for the player.

## Deliberate normalisations and open approvals

- The source appendices contain lesson-number drift (`2.7`/`3.7`) and answer-key labels that do not match the lesson maps. The package uses stable lesson order and a final knowledge-check lesson per block.
- The generic calibration cases do not include a particular approved FTNZ competency or assessment criterion. They are labelled reasoning practice and do not invent a pass/fail outcome.
- The Block 1 correction review supersedes the earlier formative-only position for that block: Block 1 now requires 100% on the knowledge check and allows no more than five attempts. Blocks 2 and 3 retain their existing formative configuration pending separate FTNZ review.
- Block 1 completion is sequential and set to `enforce`. Required response fields are checked in the learner before progression, and the reading/scroll evidence floor also applies to public learners. Reflection text remains browser-local and is not included in the emailed completion record.
- Block 1 now creates a non-certificate completion record after a verified 100% quiz result. The learner enters their name and CAA participation ID; the server adds the course title and completion date, stores the record in tenant D1 and sends fixed-recipient notifications to Steve Kingsbury and Diana Franklin.
- Block availability is represented as three separate course entries so FTNZ can assign one block at a time. The live tenant must still maintain the intended cohort/course access rows before operational delivery.
