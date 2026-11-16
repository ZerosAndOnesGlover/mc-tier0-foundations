# MC 001 · Numbers and Number Sense

**Course:** MC 001, Numbers and Number Sense (Tier 0, 6 weeks)
**When:** Mon 16 Nov 2026 – Sun 3 Jan 2027 · **Status:** complete
**Course material:** `0. Tier 0 - Foundations/0. MC 001 - Numbers and Number Sense/`
**Shell variable:** `$MC001` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Most of the trouble people have with algebra and calculus starts here, hidden. When it isn't clear *why* −3 × −4 =
12, what ¾ "is", or why 2⁰ = 1, every rule built on top has to be memorised, and memorised rules fall apart
under pressure. This course rebuilds **number sense**, the ability to *see* what a number is doing, from the very
beginning. It's a computer scientist's version: bases 2 and 16 are there from the first lecture, and the course
ends with how a computer actually stores numbers.

**Needs:** nothing. **Unlocks → CSE:** MATH 141 Week 0 (algebra and exponent review), ECE 110 (number systems), PROG 101 (integer types), CS 101 (data representation).

This folder holds everything submitted for MC 001: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 16 – Sun 22 Nov 2026 | A numeral is a recipe whose meaning comes from position; a negative number is a place and a move on a line that runs both ways. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 23 – Sun 29 Nov 2026 | A fraction is a division waiting to happen, and ratios, rates and percentages are the same idea in different clothes. | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 30 Nov – Sun 6 Dec 2026 | Powers are repeated multiplication, and a⁰ = 1 and a⁻ⁿ = 1/aⁿ are what the pattern forces. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 7 – Sun 13 Dec 2026 | The order of operations isn't arbitrary, and the distributive law is a rectangle. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 14 – Sun 20 Dec 2026 | Primes are the atoms of multiplication, and remainders are clock arithmetic. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 28 Dec 2026 – Sun 3 Jan 2027 | A computer stores numbers on a fixed odometer, and every surprise comes from that. | Final |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 16 (Practice 5 · Lab 5 · Quiz 5 · Final 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/0 Tier0 Foundations/MC 001.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
mkdir -p "$MC001/week1" && cd "$MC001/week1"     # the lab's own Setup block gives the right week
java Lab.java                                    # Java 25 compact source files, run in place
```

Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 001 · Mathematics for Computing · Submissions*
