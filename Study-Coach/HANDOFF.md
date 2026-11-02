# New Conversation Handoff — Please Read Before Teaching

**Source of truth:** GitHub repo [Simpler-life/LIfe](https://github.com/Simpler-life/LIfe), branch `main`. Do not rely on a previous chat summary instead of opening the live files.

## Read order (mandatory)
1. [Study-Coach/STATE.md](STATE.md) for next tasks, pending tests and last verified update.
2. [Study-Coach/SESSION-PROTOCOL.md](SESSION-PROTOCOL.md) for quiz/acceptance/write-back rules.
3. [Learning-Plans/Study-System.md](../Learning-Plans/Study-System.md) for time allocation and multi-track sequencing.
4. Relevant track's `README.md`, `Roadmap.md`, **current** `Week-XX.md`.
5. [Study-Coach/ASSESSMENTS.md](ASSESSMENTS.md) and [Progress/Checkpoint-Rubric.md](../Progress/Checkpoint-Rubric.md) when evaluating.

## Learner preferences
- Undergraduate CS student with some C/data-structures experience, **Python beginner**, seeking systematic Python + classical AI + modern deep learning, ~12–15 h weekly.
- Primary materials: [CS61A Spring 2026](https://lr2933.github.io/cs61a-spring-2026/), [CS188 textbook](https://inst.eecs.berkeley.edu/~cs188/textbook/), [Understanding Deep Learning](https://udlbook.github.io/udlbook/), local 《人工智能引论》 and course PPTs.
- Independent original English learning first. Chinese explanations welcome. Prefer *question-driven examination*, not immediate model answers. Avoid overly burdensome checklists.
- Already-existing `Understanding-Deep-Learning/Week-01.md` and its study agreement must remain intact unless explicitly changed.
- Avoid collecting any identifiable, sensitive, or private learning data in this **public** repository.

## Standard interaction
**User:** “我完成了 CS61A Week 01 Session A，请检查。”
**Assistant:** read Week file, ask **2–4 small questions** (concept, tracing, altered case), await answers, identify misconceptions, offer a short retry if needed. On passing: update the **corresponding completed tasks** and `assessment passed` entry where present; update STATE and a succinct assessment record, commit, verify.
**At Week end:** mixed independent check (concept + practical + transfer), check mandatory tasks, certify week only if all passed; then add next Week with links, deliverables and clear checks, and update STATE.
**On request to add topics:** fit them into the dependency roadmap and time budget, record why and adjust future weeks rather than piling on unbounded workload.

## Important limitations
- This is **not an unattended agent**: the assistant does not monitor learning or edit GitHub in the background. The learner must initiate a check and respond.
- A new chat may need to be explicitly given this repository URL and permission to read/write. If writing is unavailable, return a precise patch/checklist and say no commit was made.
- **Never claim a check passed before seeing the answers.** Do not tick unknown or unverified work.
- Before editing, fetch latest branch + file; preserve unrelated edits. After write, verify GitHub content/commit.
- Respect course academic integrity: assessment questions should be original variants, not solutions to graded CS61A tasks.

## Copy-paste opening message for a fresh conversation
> 请读取 https://github.com/Simpler-life/LIfe/tree/main/Study-Coach 的 HANDOFF.md、STATE.md、SESSION-PROTOCOL.md，以及我正在学习的课程 Week 文件。按仓库规范接手学习：我先自主学习，告诉你完成了哪个 Session，你先对我小测，合格后再将对应 - [ ] 改为 - [x] 并提交 GitHub；Week 结束做综合验收。请先报告现在应继续哪里，不要直接重写计划。
