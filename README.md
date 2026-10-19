# STEP SEM-3 Week 5 — Java Arrays and Methods (Category C)

Solutions for all five problems in the supplied PDF.

1. **Hackathon Score Curve Booster** — modifies the original array in place and prints it with `Arrays.toString`.
2. **Duplicate Team Name Finder** — nested loops, case-sensitive comparison, no Collections.
3. **Top-3 Podium Finder** — single pass with three running variables; no sorting.
4. **Hackathon Seating Grid Optimizer** — private `rowAverage` helper, supports jagged rows, classifies against threshold.
5. **Placement Drive Shortlisting & Ranking Engine** — overloaded eligibility methods, encapsulated `Candidate`, `Comparable`, and `Arrays.sort`.

For Problem 5, the PDF explicitly allows choosing the thresholds. This solution uses CGPA >= 7.5 for direct eligibility, or CGPA >= 6.5 and coding score >= 60 for the combined check. The composite score is CGPA * 10 + coding score * 0.5, matching the sample output.

## Compile and run
Use Java 8 or later. From the `src` directory, compile and run each program separately, e.g.:

```bash
javac Problem1HackathonScoreCurveBooster.java
java Problem1HackathonScoreCurveBooster
```
