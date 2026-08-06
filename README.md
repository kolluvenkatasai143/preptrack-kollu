# PrepTrack — Placement Preparation Performance Analyzer

## Project Overview

<!-- Write 2–4 sentences in your own words covering:
     - what the application does
     - what information it collects
     - what analysis it performs
     - what final result it displays -->

PrepTrack is a Python console application that evaluates a student's placement-preparation performance. It collects the student's profile details, attendance, project and profile-verification status, and seven daily coding-practice scores. It then analyzes attendance, scoring trends, and consistency to determine passed/failed days, highest and lowest scores, and any critical performance issues. Finally, it displays a placement-readiness decision along with the primary blocker (if any) and the recommended next action.

## Features Implemented

- Student-profile input (name, registration number, graduation year)
- Attendance validation (0–100)
- Yes-or-no input validation for project and profile status
- Seven-day practice score processing using a single loop
- Absent-day handling (`-1`) using `continue`
- Score classification (Strong / Satisfactory / Needs Improvement / Critical)
- Passed and failed day counting
- Highest and lowest score detection (without `max()`/`min()`)
- First critical-score detection
- Total and average score calculation (without `sum()`), with division-by-zero prevention
- Placement-readiness evaluation using combined Boolean conditions
- First-blocker priority logic for final status
- Full formatted final report

## Python Concepts Used

- `input()`, `int()`, `float()`
- Variables, meaningful naming, f-strings
- Boolean expressions and compound conditions
- `if` / `elif` / `else`, including nested conditions
- `while` loops for input validation (`break`)
- `for` loop with `range()` for the seven-day cycle
- `continue` for skipping absent days
- Counter and accumulator variables
- Arithmetic, relational, and logical operators

## How to Run

```bash
python main.py
```

Depending on your system configuration:

```bash
python3 main.py
```

## Test-Result Summary

| Test ID | Scenario                     | Expected Result                 | Actual Result | Status |
| ------- | ----------------------------- | -------------------------------- | -------------- | ------ |
| TC-01   | All requirements satisfied    | Ready for Mock Interview         |                |        |
| TC-02   | Critical score present        | Critical Support Required        |                |        |
| TC-03   | Fewer than six attempts       | Practice Incomplete              |                |        |
| TC-04   | Fewer than four passes        | Insufficient Passed Practices    |                |        |
| TC-05   | Average below 70              | Practice Improvement Required    |                |        |
| TC-06   | Attendance below 75           | Attendance Improvement Required  |                |        |
| TC-07   | Graduation year not eligible  | Graduation Criteria Not Met      |                |        |
| TC-08   | Project incomplete            | Application On Hold              |                |        |
| TC-09   | Profile not verified          | Application On Hold              |                |        |
| TC-10   | All days absent               | Practice Not Evaluated           |                |        |
| TC-11   | Invalid low score              | Input rejected                   |                |        |
| TC-12   | Invalid high score             | Input rejected                   |                |        |
| TC-13   | Boundary scores                | Correct classifications          |                |        |
| TC-14   | Multiple blockers              | First blocker displayed          |                |        |

<!-- Use "Pass" or "Fail" in the Status column. Only fill this in after you have actually run each test yourself. -->

## Individual Contribution

```
Name:

Repository URL:

My main contribution:

Features I implemented:

Python concepts I used:

Most difficult logic:

Problem I faced:

How I solved it:
```

<!-- Fill this in honestly with your own experience building the project. -->

## Code Review Completed

| Reviewed Member | Repository Link | What Was Done Well | Issue Identified | Suggested Improvement |
| ---------------- | ----------------- | -------------------- | ------------------- | ------------------------ |
|                   |                    |                       |                      |                           |

<!-- Fill this in after you actually review your assigned teammate's repository.
     Be specific — avoid generic feedback like "good code" or "well done". -->

## Feedback Received

```
Reviewed By:

Feedback Received:

Was the Feedback Valid? Yes / No

Change Made:

Commit Message Used:
```

<!-- Fill this in after your own repository has been reviewed and you've applied any valid feedback. -->
