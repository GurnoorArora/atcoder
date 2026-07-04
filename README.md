# AtCoder Roadmap: Gray → Blue

**Assumptions:** You know basic DS&A (NeetCode 150 level) and C++ STL. This roadmap fills the gap between "interview DSA" and "competitive programming," which is mostly: speed, math, greedy/proof-thinking, and CP-specific structures.

**Blue = rating 1600–1999.** Realistic timeline with consistent practice (1–2 contests/week + upsolving): **6–12 months**, depending on hours invested.

---

## 0. Setup (Week 0)

- Make an AtCoder account, join **ABC (AtCoder Beginner Contest)** every week — always compete live (rating placement + time pressure is the actual skill you're training).
- Install [AtCoder Problems](https://kenkoooo.com/atcoder/) — this is your command center: heatmap, difficulty-tagged problem lists, virtual contests, recommended problems by your rating.
- Build a fast I/O + template snippet (fast cin/cout, common macros, modint if you like).
- Get familiar with **cp-algorithms.com** — you'll reference it constantly for algorithm write-ups.
- Learn to read editorials (many ABC editorials have English translations; use them after every contest, solved or not).

---

## Phase 1 — Gray → Brown (~0–800)
**Goal:** Never lose to implementation. Solidify basics under time pressure.

Topics:
- Careful implementation / simulation problems (this trips people up more than algorithms at this level)
- Sorting, prefix sums, basic greedy
- Brute force + complexity estimation (know what 10^8 ops "feels" like)
- Basic math: GCD/LCM, modular arithmetic basics, divisors
- STL fluency in a CP context: `map`, `set`, `pair`, `sort` with comparators, `lower_bound`/`upper_bound`

Practice: Solve ABC A–C problems consistently, then start pushing into D.

---

## Phase 2 — Brown → Green (~800–1200)
**Goal:** Build your core DP and graph toolkit.

Topics:
- **DP basics:** knapsack (0/1, unbounded), LIS, coin change, grid DP, LCS
- **Graphs:** BFS/DFS, connected components, basic tree traversal, cycle detection
- Two pointers, sliding window (you likely know these from NeetCode — now apply at CP speed)
- Binary search on the answer (not just on arrays)
- Basic combinatorics: nCr, factorials mod p
- Union-Find (DSU) — learn it now, you'll use it everywhere later

Practice: Target ABC D problems as your bread and butter; start attempting E occasionally.

---

## Phase 3 — Green → Cyan (~1200–1600)
**Goal:** This is where "real" competitive programming begins.

Topics:
- **DP:** bitmask DP, digit DP, tree DP, DP on intervals
- **Graphs:** Dijkstra, 0-1 BFS, MST (Kruskal/Prim), topological sort, DSU with union by rank/path compression
- **Number theory:** Sieve of Eratosthenes, modular inverse, Euler's totient, combinatorics mod p with precomputed factorials
- Segment Tree and Fenwick Tree (BIT) — point update/range query, range update/point query
- Meet in the middle
- Coordinate compression
- Stronger greedy proofs (exchange argument, exchange + induction)

Practice: ABC E/F become your target zone. Start doing **ARC (AtCoder Regular Contest)** A/B problems too — they train harder math/constructive thinking that ABC doesn't emphasize as much.

---

## Phase 4 — Cyan → Blue (~1600–1999)
**Goal:** Depth and pattern recognition across harder structures; contest speed on mid-difficulty problems so you have time for the hard one.

Topics:
- **Advanced DP:** DP optimization (convex hull trick, divide & conquer optimization — as needed), DP with segment tree/BIT acceleration, digit DP variants
- **Graphs:** LCA (binary lifting), Euler tour + segment tree for subtree/path queries, SCC (Tarjan/Kosaraju), 2-SAT basics
- **Data structures:** Lazy propagation segment trees, sqrt decomposition, sparse tables (RMQ)
- **Math:** Extended Euclid, CRT basics, matrix exponentiation, more combinatorics (inclusion-exclusion, Catalan-type problems)
- **Game theory:** Grundy numbers / Sprague-Grundy, Nim
- Constructive algorithms (common in ARC) — these are more about creative proof-based thinking than memorized algorithms
- **AtCoder Library (ACL):** learn to use it directly (DSU, segtree, lazy segtree, modint, mincostflow) — saves huge implementation time in contest

Practice: ABC F/G, ARC C/D. Do **virtual contests** of past ARCs under time pressure specifically for the constructive/math flavor.

---

## Weekly Practice Structure (once past Phase 1)

1. **Live contest:** every ABC (and ARC when you can). Always submit something even if you don't finish.
2. **Upsolve within 48 hours:** finish every problem you didn't solve live, using editorial only after 20–30 min of genuine struggle.
3. **1–2 virtual contests/week** from past contests slightly above your current comfort (use AtCoder Problems' recommendation feature).
4. **Keep an error log:** every time you get WA/TLE, write one line on *why* — pattern recognition compounds fast this way.
5. **Revisit topics, not just problems:** if you struggle with a segment tree problem, don't just solve that problem — do 3–4 more segment tree problems that week.

---

## Key Resources

- [AtCoder Problems](https://kenkoooo.com/atcoder/) — problem lists by difficulty, virtual contests, heatmap
- [cp-algorithms.com](https://cp-algorithms.com) — algorithm reference/write-ups
- [USACO Guide](https://usaco.guide) — excellent topic-by-topic curriculum (Bronze→Platinum maps roughly to Gray→Blue+ and beyond), great supplementary explanations
- [AtCoder Library (ACL)](https://github.com/atcoder/ac-library) — start using this once you hit Phase 3
- Editorials (公式解説) — read every single one after every contest, even for problems you solved, to see if there was a cleaner approach

---

## Mindset Notes

- **Rating is noisy short-term, honest long-term.** Don't overreact to one bad contest.
- CP rewards **speed + correctness** on "known" patterns more than raw cleverness — most of the climb from Green to Blue is pattern inventory, not IQ.
- ARC problems (especially the earlier ones, A/B) are fantastic for building the "constructive/proof" muscle that pure DP/graph grinding won't give you.
- Don't skip the math phase — a lot of Cyan/Blue problems are blocked by a missing number theory or combinatorics trick, not by not knowing a fancy data structure.
