# AI Foundations — Complete Roadmap

Each module advances only when its checkpoint passes. Adapt time based on current CS61A prerequisites. 3–4 h/week is a baseline, not enough to race through every chapter in one week.

| Module | Exact CS188 location | ZJU relationship | Proof of learning |
| --- | --- | --- | --- |
| A1 Search formulation | Ch 1 §1.1–1.4 | Ch 3: state, actions, BFS/DFS/UCS/Greedy/A* | hand trace and independently code search (CP-02) |
| A2 Constraint solving | Ch 2 §2.1–2.5 | 8 queens and related CSPs | variables/domains/constraints; compare backtracking and pruning |
| A3 Adversarial games | Ch 3 §3.1–3.5 | Ch 3/7: minimax, alpha-beta, UCB, MCTS | worked game tree, legal game agent, 10+ trials (CP-03) |
| A4 Formal logic | Ch 10 §10.1–10.9 | Ch 2: proposition, predicate, resolution, knowledge graph | formalize statements, justify inference |
| A5 Probabilistic inference | Ch 6 §6.1–6.7; Ch 8 | Ch 2 probabilistic graphs, causes | Bayes net, independence and numerical inference (CP-05) |
| A6 Decisions & RL | Ch 4; Ch 5 | Ch 6: Bellman, Q-learning, exploration | gridworld value/Q update and implementation |
| A7 Classical ML | Ch 9 + StatQuest videos | Ch 4: regression, decision trees, K-means, PCA/LDA | baseline/evaluation + error analysis (CP-06) |
| A8 AI ecosystems & limits | ZJU Ch 7–10 + reliable modern docs | game theory, ethics, systems and applications | scenario-based design and limitations memo |

**ZJU-only supplements:** FOIL, PRA, causal graphs and interventions, evolutionary learning, Nash equilibrium, hardware/software overview. Do not treat CS188 as covering them automatically. Consult [mapping](Course-Mapping.md).

**Sequencing note:** A1–A3 may be prioritized for the current MCTS lab. A4–A7 follow when Python/probability foundation supports them. Neural-network depth is assigned to the separate UDL track.
