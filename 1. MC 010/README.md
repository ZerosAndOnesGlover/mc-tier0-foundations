# MC 010 · Algebra

**Course:** MC 010, Algebra (Tier 0, 12 weeks)
**When:** Mon 4 Jan 2027 – Sun 28 Mar 2027 · **Status:** complete
**Course material:** `0. Tier 0 - Foundations/1. MC 010 - Algebra/`
**Shell variable:** `$MC010` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Algebra is arithmetic with some of the numbers left unnamed. In MC 001 you found out *why* the laws of arithmetic hold;
here you use exactly those laws on letters, so that one line can speak about every number at once, or corner a number
you haven't found yet. Nothing in this course is a trick to memorise. "Move it to the other side", "FOIL" and
"cross-multiply" each turn out to be a law you already know, and the course always says which one.

**Needs:** MC 001. **Unlocks → CSE:** MATH 141 Weeks 0–5, PHYS 141 (every formula), MATH 151 notation, CS 102 (log n).

This folder holds everything submitted for MC 010: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 4 – Sun 10 Jan 2027 | A letter is a number you haven't named yet, and simplifying is the laws of arithmetic used on purpose. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 11 – Sun 17 Jan 2027 | An equation is a balance: do the same to both sides, and it stays true. | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 18 – Sun 24 Jan 2027 | An inequality is a balance that can tip; absolute value is distance.* CSE Spring starts this week. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 25 – Sun 31 Jan 2027 | A function is a machine: one input, one output, and a graph is its whole table drawn at once. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 1 – Sun 7 Feb 2027 | Slope is a rate: how much the output changes per unit of input. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 8 – Sun 14 Feb 2027 | Two equations, two unknowns: where two lines meet. | Lab 6 · Practice 6 · Quiz 6 |
| 7 | Mon 15 – Sun 21 Feb 2027 | Multiplying brackets is finding an area; factoring is finding the rectangle's sides. | Lab 7 · Practice 7 · Quiz 7 |
| 8 | Mon 22 – Sun 28 Feb 2027 | Every parabola is one shape, moved; the quadratic formula is completing the square, done once for all. | Lab 8 · Practice 8 · Quiz 8 |
| 9 | Mon 1 – Sun 7 Mar 2027 | A root is a factor: $p(r) = 0$ exactly when $(x - r)$ divides $p$.* CSE midterm week: keep it light. | Lab 9 · Practice 9 · Quiz 9 |
| 10 | Mon 8 – Sun 14 Mar 2027 | Exponential means multiplying by the same factor each step; a logarithm counts the steps. | Lab 10 · Practice 10 · Quiz 10 |
| 11 | Mon 15 – Sun 21 Mar 2027 | The log laws are the exponent laws read backwards. | Lab 11 · Practice 11 · Quiz 11 |
| 12 | Mon 22 – Sun 28 Mar 2027 | Add a list to itself backwards, and every pair has the same sum. | Final |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 34 (Practice 11 · Lab 11 · Quiz 11 · Final 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/0 Tier0 Foundations/MC 010.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
mkdir -p "$MC010/week1" && cd "$MC010/week1"     # the lab's own Setup block gives the right week
java Lab.java                                    # Java 25 compact source files, run in place
```

Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 010 · Mathematics for Computing · Submissions*
