# AI Foundations — Week 01: Search is problem solving

**Budget:** 3–4 hours, flexible days. **Goal:** explain state/action/search, trace BFS and DFS and distinguish optimality from completeness. Python optional for Week 01.

## Direct resources
- [CS188 Textbook §1.1 Agents](https://inst.eecs.berkeley.edu/~cs188/textbook/Search/Agents.html)
- [CS188 §1.2 State Spaces and Search Problems](https://inst.eecs.berkeley.edu/~cs188/textbook/Search/StateSpaces.html)
- [CS188 §1.3 Uninformed Search](https://inst.eecs.berkeley.edu/~cs188/textbook/Search/UninformedSearch.html)
- Fallback: [CS188 textbook Chapter 1 navigation](https://inst.eecs.berkeley.edu/~cs188/textbook/) if a deep link changes.
- Local: 《人工智能引论》第3章 + 第三章 PPT（本项目资料），搜索基本概念和无信息搜索。

## Session A — formulate (~60–75 min)
- [ ] Read §1.1–1.2 and corresponding local chapter notes.
- [ ] For a city-route / 8-puzzle problem write: state, initial state, actions, transition, goal test, path cost.
- [ ] **R check:** explain why a search tree differs from the underlying state graph and why repeated states matter.

## Session B — trace (~60–90 min)
- [ ] Read §1.3 and trace BFS and DFS on a graph you draw (>=7 nodes, at least one cycle).
- [ ] Write frontier/visited sets after each expansion; state tie-breaking order.
- [ ] **P check:** identify returned path and number of expansions; compare completeness, optimality and memory.

## Session C — transfer and review (~60–75 min)
- [ ] Modify an edge or add a cycle to graph, **predict** effects on BFS/DFS with no notes.
- [ ] **T check:** explain conditions where BFS is shortest path and why DFS need not be.
- [ ] Connect to your 8-queens experience: how to specify state and legal next actions.
- [ ] Ask ChatGPT to **quiz with a new graph** after your independent attempt; correct any errors.
- [ ] Week 01 check PASS (R+P+T+reflection; else RETRY).

**Next:** UCS, Greedy and A*, then CSP, minimax, alpha-beta, UCB/MCTS. For the current lab, use [MCTS/Reversi](MCTS-and-Reversi.md) in parallel.
