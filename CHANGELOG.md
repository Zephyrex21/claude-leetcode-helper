# Changelog

All notable changes to this project are documented here.

---

## [2.0.0] — 2025

### Added

- **Hint Mode** — guiding nudge shown before every full solution by default;
  skipped only when the user explicitly says "skip hint" or "just give solution".
- **Brute Force First rule** — naive C++ solution with complexity is always
  shown before the optimized approach, building genuine intuition.
- **Answer Header** — every answer now opens with Difficulty, Topic, and Pattern tag.
- **Pattern Recognition Table** — 17 patterns mapped to their C++ STL containers
  in both SKILL.md and AGENTS.md.
- **STL Toolbox section** — lists every container used in the solution and explains
  exactly why it was chosen.
- **"Why Not X?" subsection** — rejects the most obvious alternative approach with
  clear one-to-two line reasoning.
- **Visual Dry Run rules** — format selected by problem type: table for array/hash,
  ASCII pointer diagram for two pointers, ASCII bracket diagram for sliding window,
  ASCII tree for tree problems, filled table for DP.
- **C++ Pitfalls section** — flags signed/unsigned mismatch, integer overflow,
  `operator[]` vs `.count()`, DP base case initialization, binary search
  off-by-one, max-heap vs min-heap, and more.
- **Interview Tips section** — tells the user exactly what to say out loud at
  each stage: opening, trade-off, key lines, and closing.
- **Similar Problems section** — 2–3 related LeetCode problems using the same
  pattern, with the variation noted.
- **Solution Quality Checklist** expanded to cover all 14 new sections.
- **AGENTS.md** fully rewritten with 17 numbered section rules, priority ordering,
  and per-section output format examples.
- **README.md** rewritten with feature table, folder structure, example output
  structure, and full pattern list.

### Changed

- Default language confirmed as C++ throughout.
- Dry run is no longer always a table — format is now chosen based on problem type.
- Brute force mention in v1.0.0 was optional; in v2.0.0 it is mandatory and must
  include compilable C++ code.

---

## [1.0.0] — 2025

### Added

- Initial release.
- C++ as default language with `class Solution` style.
- Owner: Saurabh Raj Shekhar (github.com/Zephyrex21).
- Core sections: Problem Understanding, Approach, Algorithm, Code,
  Line-by-Line Explanation, Dry Run, Complexity, Edge Cases.
- Priority system (CRITICAL / HIGH) in AGENTS.md.
- Solution Quality Checklist.
- Repo structure: SKILL.md, AGENTS.md, README.md, LICENSE, CHANGELOG.md,
  CONTRIBUTING.md, .gitignore.
