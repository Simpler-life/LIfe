# Integrated Study System — 12–15 hours / learning week

## Goal and scope
Build independent Python software skills, classical AI reasoning/search/planning, and modern deep-learning literacy. This is an **estimated 9–12+ month roadmap, not a guarantee or a deadline**. 40–48 learning weeks may take longer when projects or exams intervene.

## Weekly allocation (initial)
- CS61A / Python — **5–6 h**: 2–3 lectures/textbook sessions + 2–3 h independent practice.
- AI Foundations / CS188 & ZJU — **3–4 h**: 1 reading, 1 diagram/math problem, 1 implementation or proof.
- Understanding Deep Learning — **~3 h**: existing 3 sessions (40–60 min), unchanged.
- Math & retrieval / review — **1–2 h**: explain from memory, correct misunderstandings, math as needed.

Prefer 5–6 study blocks across the week; never tie sessions to specific weekdays. Allocate only real focused hours. Busy week: preserve **one CS61A session + one UDL session**, shift everything else without catch-up debt. Intense school-lab week: temporarily use the AI block for that lab; do not double-count study time.

## Dependencies and 5 phases

| Phase | Indicative learning weeks | Python / CS61A | AI Foundations | UDL and applied outcome |
| --- | --- | --- | --- | --- |
| 1. Foundations | 1–6 | functions, control, higher-order functions, recursion, lists | state spaces, BFS/DFS/UCS/A* | current UDL introduction; tiny search programs |
| 2. Classical AI | 7–14 | data abstraction, trees, OOP, projects | CSP, minimax, alpha-beta, MCTS, logic | NN basics; MCTS/other game agent |
| 3. Probability & ML | 15–24 | interpreters, iterators, Scheme/SQL (as per syllabus) | Bayes nets, HMM, MDP, Q-learning, regressions, trees, clustering | from-scratch regression / tiny neural net |
| 4. Deep learning | 25–36 | practical NumPy/PyTorch beyond CS61A | topic consolidation + benchmark | CNN, optimization, transformer; training scripts |
| 5. Systems and application | 37–48+ | tests, modules, packaging, APIs | ethics, agent planning, limits | generative models, RAG/agent evaluation; one end-to-end project |

These are **planning bands**, not fixed week-by-week simultaneous requirements; UDL advances by its own checkpoints. Finish one sequence before jumping ahead. Some ZJU-specific topics are covered by local textbook rather than CS188 (e.g. FOIL/PRA, causal methods, evolutionary learning).

## Assessment gates
- **Session**: no-source explanation + assigned independent practice.
- **Track checkpoint**: one unseen transfer task, with errors logged and explained.
- **Phase gate**: working artifact / worked derivation + short written interpretation; see [rubric](../Progress/Checkpoint-Rubric.md).
- **Capstone**: repository with runnable instructions, baseline, test/evaluation, limitations and postmortem.

**Rules**: An item marked complete requires evidence; a failed checkpoint creates a targeted reattempt, not a vague restart. ChatGPT can act as oral examiner **after** your attempt and should test the same idea with changed examples, not supply answer keys in advance.

## Next steps
1. Finish current [UDL Week 01](Understanding-Deep-Learning/Week-01.md) without rewriting it.
2. Start [CS61A Week 01](CS61A-Python/Week-01.md) and [AI Week 01](Artificial-Intelligence/Week-01.md).
3. At the end of each **four completed learning weeks** perform a phase readiness check and adjust next-week workload.
4. Keep programming artifacts in independent repos; link them here, avoid pasting solutions in a public planning repo.
