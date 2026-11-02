# Learning Verification and GitHub Update Protocol

## Terminology
- **Task**: one checkbox line of a Week file; may be reading, writing, practice, self-check, or assessment.
- **Session**: a labeled block within a Week (e.g. CS61A Week 01 Session A; UDL Session 1).
- **Mini-check**: a short interactive assessment after the learner reports Session done.
- **Week gate**: cumulative review across that Week, not merely sum of ticked readings.
- **Milestone**: CP-01 ... CP-09 in [rubric](../Progress/Checkpoint-Rubric.md).

## 1. When learner says a Section/Session is finished
1. Fetch up-to-date GitHub `Week-XX.md` + `STATE.md`. Distinguish completed tasks from claims of mastery.
2. Verify what the Session actually required and ask **2–4 questions** in one turn:
   - 1 conceptual explanation in the learner's own words;
   - 1 tracing/calculation/problem-solving task;
   - 1 changed example/new requirement to check transfer, if feasible.
3. **Do not give answers before attempting**, except on explicit tutoring request. Adapt difficulty to syllabus; allow Chinese clarification; English feedback where useful.
4. Evaluate response with **PASS / RETRY**. PASS requires sound key concepts **and** correct reasoning for practical/transfer questions. One minor slip may be corrected immediately; a fundamental error requires a new focused question.
5. On PASS, mark verified task(s) `- [x]` in that Session. Where no Session-specific PASS item exists, **add** `- [x] Session A mini-check passed (YYYY-MM-DD)` beneath its section. Do not tick tests that were not attempted. Mark reading/practice only after the learner confirms actually doing them.
6. On RETRY, **do not tick PASS**; tell learner the minimum specific topic to revisit and assess with a *new* variant later.

**Example:** “CS61A Week 01 Session A 已完成” triggers questions about `def`, parameters/`return`, a short function trace and a changed case—not the Week's overall acceptance.

## 2. At end of each Week
Prerequisites: every mandatory Session task actually completed; all Session mini-checks passed (or explicitly reconciled against a documented equivalent).
- Give a short **mixed assessment**: one concept, one unseen practical computation/code/derivation, one transfer/failure-case explanation across the Week.
- Validate responses and overall ability. If incomplete, keep Week open, write focused next-step tasks.
- On PASS, tick `Week ... assessment PASSED` or equivalent overall checkbox (create if absent) **and** update STATE/ASSESSMENTS.
- Plan the next Week *only after* pass. Add exact source URLs / sections, estimated study sessions, goals, independent practice, mini-check, week-gate questions, and measurable exit criteria.

## 3. GitHub write-back — atomic, minimal, auditable
After a PASS or an expressly verified completed action:
- Re-fetch target Week file, `STATE.md`, `ASSESSMENTS.md` from `main`.
- Update relevant checkboxes **only**, preserving text and other checkboxes; add missing assessment checkbox in context if necessary.
- Record status and high-level evidence in STATE, concise line in ASSESSMENTS (no verbatim student answers or graded solutions).
- Commit changes to `main` with message `study: verify <track> Week XX Session Y` or `study: pass <track> Week XX`.
- Re-read GitHub to verify. Give a direct link to the updated Week and commit. If write fails, say so and do not claim success.
- Avoid erasing existing checked progress or overwriting concurrent modifications. On divergence, refresh and merge.

## 4. Rules for personalized adaptation
- If explanation is shaky, create a short targeted review block rather than escalating to the next chapter.
- If a topic is mastered quickly, use a challenging transfer or optional extension instead of rote repetition.
- If school workload rises, reduce sessions, not quality gate or learning agreement.
- Update [CHANGE-PROTOCOL.md](CHANGE-PROTOCOL.md) for structural modifications.
- Keep learner agency: it is the learner's responsibility to report study effort and answer questions; assistant evaluates evidence and can help commit.

## 5. Explicit meaning of passing
**Session PASS** is a *local* concept/practice check, **not** a certification of the entire course. **Week PASS** requires synthesis and prerequisites. **Milestone PASS** requires a larger project/novel task. Their thresholds intentionally differ.
