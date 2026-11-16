# MC 020 · Geometry and Trigonometry

**Course:** MC 020, Geometry and Trigonometry (Tier 0, 10 weeks)
**When:** Mon 29 Mar 2027 – Sun 13 Jun 2027 · **Status:** complete
**Course material:** `0. Tier 0 - Foundations/2. MC 020 - Geometry and Trigonometry/`
**Shell variable:** `$MC020` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Geometry is the maths of shape and position; trigonometry is the maths of turning. Every game camera, sound wave and robot
arm runs on them. This course builds both from pictures: an angle is an amount of turning, $\sin$ and $\cos$ are the shadows of a
point going round a circle, and each identity is one picture seen two ways. Nothing is "SOH CAH TOA, memorise it": every
formula comes with the drawing that rebuilds it.

**Needs:** MC 010. **Unlocks → CSE:** MATH 141 Week 0 (trig review), PHYS 141 (vectors, waves), CS 422 (graphics), ECE 211 (sinusoids), CS 421 (robotics).

This folder holds everything submitted for MC 020: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 29 Mar – Sun 4 Apr 2027 | An angle is an amount of turning, and a triangle's angles add up to half a turn. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 5 – Sun 11 Apr 2027 | Similar shapes are scaled copies: lengths scale by $k$, areas by $k^2$. | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 12 – Sun 18 Apr 2027 | π is how many diameters fit round a circle, and a circle's equation is Pythagoras.* Last week of CSE teaching. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 26 Apr – Sun 2 May 2027 | $\sin$, $\cos$ and $\tan$ are the ratios that one angle fixes in every right triangle.* CSE summer break begins. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 3 – Sun 9 May 2027 | A radian is the angle whose arc equals the radius; the unit circle gives trig for every angle. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 10 – Sun 16 May 2027 | Sine is the height of a point going round a circle, drawn against time. | Lab 6 · Practice 6 · Quiz 6 |
| 7 | Mon 17 – Sun 23 May 2027 | Every trig identity is a picture of a triangle or a rotation. | Lab 7 · Practice 7 · Quiz 7 |
| 8 | Mon 24 – Sun 30 May 2027 | A vector is a move: an arrow with a length and a direction. | Lab 8 · Practice 8 · Quiz 8 |
| 9 | Mon 31 May – Sun 6 Jun 2027 | A graphics engine is rotations, scalings and translations, one after another. | Lab 9 · Practice 9 · Quiz 9 |
| 10 | Mon 7 – Sun 13 Jun 2027 | Area counts unit squares and volume counts unit cubes. | Final |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 28 (Practice 9 · Lab 9 · Quiz 9 · Final 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/0 Tier0 Foundations/MC 020.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC020/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 020 · Mathematics for Computing · Submissions*
