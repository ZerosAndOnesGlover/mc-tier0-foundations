# Tier 0 · Foundations · Submissions

**Programme:** Mathematics for Computing, a self-study track (MC 001 to MC 350)
**Tier 0:** Foundations: MC 001, MC 010, MC 020, MC 030 · Mon 16 Nov 2026 to Sun 8 Aug 2027

This repository holds everything submitted for Tier 0: one answer sheet per graded item, and the Java code written
for each lab. Every tier of the track has its own repository, as every CSE semester does.

---

## Courses

| Folder | Course | When | Status | Sheets | Variable |
|---|---|---|---|---|---|
| `0. MC 001/` | MC 001 Numbers and Number Sense | Mon 16 Nov 2026 – Sun 3 Jan 2027 | complete | 16 | `$MC001` |
| `1. MC 010/` | MC 010 Algebra | Mon 4 Jan 2027 – Sun 28 Mar 2027 | complete | 34 | `$MC010` |
| `2. MC 020/` | MC 020 Geometry and Trigonometry | Mon 29 Mar 2027 – Sun 13 Jun 2027 | complete | 28 | `$MC020` |
| `3. MC 030/` | MC 030 Precalculus | Mon 14 Jun 2027 – Sun 8 Aug 2027 | complete | 22 | `$MC030` |

Each course folder has a README with its weeks, its topics and its sheets, then `week1/`, `week2/`, …, one per teaching
week. A week's sheets appear once its material is written, so a planned course holds only its README for now. Course
material for this tier is in the vault under `0. Tier 0 - Foundations/`.

---

## How each assessment is submitted

1. Write the answer under each heading of the answer sheet. Lab code goes in the same `weekN/` folder, and the
   sheet's **Code:** line names the files.
2. Fill in *Help I Used* and set `status: submitted` in the frontmatter.
3. Commit and push **from this folder** (it's the repository, not the vault):
   ```bash
   cd "$MC001/.."      # any course variable of this tier, then up one level
   git add -A && git commit -m "MC NNN Week N: Practice N, Lab N, Quiz N submitted" && git push
   ```
4. After grading, the sheet's `score:` is filled in, `status:` becomes `graded`, and
   `python3 tools/gpa.py --sync --write` (from the vault's `9. Track Registry/`) copies it to the gradebook.

---

## What is ignored

- `.gitignore` at the repo root applies to every course: Obsidian state, OS and editor files, Python bytecode and
  compiled Java (`*.class`). The labs run from source with `java Lab.java`, so nothing compiled needs keeping.
- The last rule, `practice/`, ignores every week's practice folder. Experiments and test code stay local, so anything
  meant for grading goes in `weekN/` itself.

---

*Tier 0 · Mathematics for Computing · `ZerosAndOnesGlover/mc-tier0-foundations`*
