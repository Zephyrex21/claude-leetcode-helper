<div align="center">

# Claude LeetCode Helper Skill

**A Claude Skill that turns any LeetCode problem into a complete, interview-ready breakdown.**

[![Version](https://img.shields.io/badge/version-2.0.0-blue?style=flat-square)](https://github.com/Zephyrex21/claude-leetcode-helper/releases)
[![Language](https://img.shields.io/badge/language-C%2B%2B-00599C?style=flat-square&logo=cplusplus)](https://en.cppreference.com/)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange?style=flat-square)](https://claude.ai)

*by [Saurabh Raj Shekhar](https://github.com/Zephyrex21)*

</div>

---

## What It Does

Paste any LeetCode problem. The skill delivers a **full interview-ready solution** — not just code, but the entire thinking process a top candidate would walk through:

```
Hint  →  Brute Force  →  Optimized Approach  →  Why Not X?
→  STL Toolbox  →  Algorithm  →  Clean C++ Code  →  Line-by-Line
→  Visual Dry Run  →  C++ Pitfalls  →  Complexity  →  Edge Cases
→  Interview Tips  →  Similar Problems
```

---

## Features — v2.0.0

| Feature | Description |
|---|---|
| **Answer Header** | Difficulty · Topic · Pattern tag on every answer |
| **Hint Mode** | Guiding nudge before the solution — skippable |
| **Brute Force First** | Naive C++ + complexity before the optimized solution |
| **Pattern Recognition** | 17 patterns mapped to their C++ STL containers |
| **Why Not X?** | Rejects the obvious alternative with clear reasoning |
| **STL Toolbox** | Every container explained with its role |
| **Step-by-Step Algorithm** | Numbered breakdown before any code |
| **Clean C++** | Accepted-style `class Solution`, no boilerplate |
| **Line-by-Line Explanation** | Every meaningful line explained |
| **Visual Dry Run** | Table · ASCII pointer diagram · ASCII window · DP table |
| **C++ Pitfalls** | Signed/unsigned · overflow · map[] · off-by-one · and more |
| **Complexity Analysis** | Time and space with clear reasoning |
| **Edge Cases** | Boundary inputs with explanations |
| **Interview Tips** | Exactly what to say at each stage |
| **Similar Problems** | 2–3 related problems using the same pattern |

---

## Installation

1. Download the latest release zip from [Releases](https://github.com/Zephyrex21/claude-leetcode-helper/releases).
2. Go to **Claude → Settings → Skills**.
3. Click **Add Skill** and select the downloaded zip.
4. Paste any LeetCode problem — the skill activates automatically.

---

## Supported Patterns

| Pattern | C++ Container |
|---|---|
| Hash Map / Set | `unordered_map`, `unordered_set` |
| Ordered Map / Set | `map`, `set` |
| Two Pointers | `left`, `right` index variables |
| Sliding Window | `left`, `right` + frequency map |
| Prefix Sum | `vector<long long> prefix` |
| Binary Search | `lower_bound`, `upper_bound`, `lo`/`hi` |
| Monotonic Stack | `stack<int>` |
| Heap / Priority Queue | `priority_queue<int>` |
| Greedy | sort + single pass |
| Backtracking | recursion + `path` vector |
| Dynamic Programming 1D | `vector<int> dp` |
| Dynamic Programming 2D | `vector<vector<int>> dp` |
| BFS | `queue<int>` + `visited[]` |
| DFS | recursion or `stack<int>` |
| Union Find | `parent[]`, `rank[]` |
| Trie | `TrieNode` struct |
| Topological Sort | BFS + in-degree array (Kahn's) |

---

## File Structure

```
claude-leetcode-helper/
├── SKILL.md          ← skill definition, output format, full example
├── AGENTS.md         ← 17 section rules with format examples
├── README.md         ← this file
├── CHANGELOG.md      ← version history
├── CONTRIBUTING.md   ← contribution guidelines
├── LICENSE           ← MIT
└── .gitignore
```

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for full version history.

**v2.0.0** — Hint mode · Brute force first · Pattern tags · STL Toolbox · Why Not X? · Visual dry runs · C++ Pitfalls · Interview Tips · Similar Problems

**v1.0.0** — Initial release

---

## Contributing

Pull requests and issues are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## Author

**Saurabh Raj Shekhar**
GitHub: [@Zephyrex21](https://github.com/Zephyrex21)

---

## License

MIT — see [LICENSE](LICENSE)
