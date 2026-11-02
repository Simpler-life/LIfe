# MCTS & Reversi — Applied AI Lab

**This is a focused companion to the complete AI track**, not a replacement for search/logic/ML. Use the provided classroom `main.ipynb`, `board.pyw`, `game.pyw`, lab PDF and report instructions.

## Resource map
1. [CS188 Games Chapter](https://inst.eecs.berkeley.edu/~cs188/textbook/) — open **3.1 Games**, **3.2 Minimax**, **3.5 Monte Carlo Tree Search** from nav.
2. Local 《人工智能引论》第3章 (§ MCTS/UCB) + 「第二次实验课 - 黑白棋.pdf」 (rules, UCB, four steps, simulation & backup).
3. Python reference: [Python tutorial](https://docs.python.org/3/tutorial/), CS61A function/recursion lectures.
4. Your actual submission and runtime limits: **use classroom files as authority**, not external example repositories. Read the local 测试提交指南 and program report template.

## Four learning gates
- [ ] **G1 Game model:** explain legal move, pass, terminal test, scoring; inspect `Board.get_legal_actions`, `Board._move`, `Board.get_winner`. Demonstrate with a small board state.
- [ ] **G2 Mathematics:** derive and calculate UCB on sample `Q_i, N_i, t, C` values; explain exploration bonus and unvisited child handling.
- [ ] **G3 Algorithm:** explain and hand-trace Selection→Expansion→Simulation→Backpropagation, including whose perspective reward is stored and sign convention.
- [ ] **G4 Implementation:** independently sketch `Node` fields and `get_move(board)` contract, implement a legal baseline, then MCTS, handle pass/timeouts/terminal states.

## Verification
- [ ] All returned moves legal in 10+ reproducible test positions; pass case handled.
- [ ] Reproduce 10+ games against specified opponents with recorded seeds/settings where available.
- [ ] Compare a baseline (random or deterministic) against MCTS; explain results and variance.
- [ ] No per-move timeout; report actual tested hardware and timing, not guessed performance.
- [ ] Provide problem restatement, key code, measured results in report; label optional sections according to classroom template.
- [ ] **Transfer:** change exploration parameter or rollout policy; predict and then measure impact.
- [ ] CP-03 PASS after a correct independent explanation + observed behavior.

**Integrity:** Follow teacher's permitted assistance rules. AI is for conceptual feedback and debugging, not concealing copied implementation.
