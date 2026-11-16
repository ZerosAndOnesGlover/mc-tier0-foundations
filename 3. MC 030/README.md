# MC 030 · Precalculus

**Course:** MC 030, Precalculus (Tier 0, 8 weeks)
**When:** Mon 14 Jun 2027 – Sun 8 Aug 2027 · **Status:** complete
**Course material:** `0. Tier 0 - Foundations/3. MC 030 - Precalculus/`
**Shell variable:** `$MC030` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Calculus is about functions, so this course makes functions familiar: their families and shapes, how to move, chain and
undo them, and the awkward ones (floor, ceiling, piecewise) that programs are full of. Then it adds the two ideas a
school course usually skips. **Complex numbers** turn out to be MC 020's rotations written as arithmetic, and **limits**
are what a quantity is heading towards when you zoom in. Every rule still comes with the picture that rebuilds it.

**Needs:** MC 020. **Unlocks → CSE:** MATH 141 (all of it, especially Weeks 0–2), ECE 211 (complex exponentials), CS 102 (floor, ceiling, logs).

This folder holds everything submitted for MC 030: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 14 – Sun 20 Jun 2027 | Every function belongs to a family, and four numbers move any graph. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 21 – Sun 27 Jun 2027 | A pipeline of machines, and running it backwards. | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 28 Jun – Sun 4 Jul 2027 | The functions programs are full of: rules with cases, distances, and rounding down. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 5 – Sun 11 Jul 2027 | Compound often enough and the growth factor becomes $e$. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 12 – Sun 18 Jul 2027 | $i$ is a quarter turn, so multiplying is rotating. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 19 – Sun 25 Jul 2027 | $e^{i\theta}$ is the unit circle, and the $n$th roots of 1 are a regular polygon. | Lab 6 · Practice 6 · Quiz 6 |
| 7 | Mon 26 Jul – Sun 1 Aug 2027 | Zoom in on a curve far enough and it looks straight. | Lab 7 · Practice 7 · Quiz 7 |
| 8 | Mon 2 – Sun 8 Aug 2027 | Infinitely many pieces can add up to something finite. | Final |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 22 (Practice 7 · Lab 7 · Quiz 7 · Final 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/0 Tier0 Foundations/MC 030.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC030/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 030 · Mathematics for Computing · Submissions*
