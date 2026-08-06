# PrepTrack — Placement Preparation Performance Analyzer

## Project Overview

PrepTrack is a Python console application that evaluates a student's placement-preparation performance. It collects the student's profile details, attendance percentage, project completion status, profile verification status, and seven days of coding-practice scores. The application analyzes attendance, score consistency, pass/fail performance, and critical issues before determining the student's placement readiness. Finally, it displays the student's overall status, the primary blocker (if any), and the recommended next action.

---

## Features Implemented

* Student profile input (Name, Registration Number, Graduation Year)
* Attendance validation (0–100)
* Project completion validation (Yes/No)
* Profile verification validation (Yes/No)
* Seven-day coding practice evaluation
* Absent-day handling using `continue`
* Score classification:

  * Strong
  * Satisfactory
  * Needs Improvement
  * Critical
* Passed and failed practice counting
* Highest score detection (without `max()`)
* Lowest score detection (without `min()`)
* First critical-score identification
* Total score calculation (without `sum()`)
* Average score calculation
* Placement readiness evaluation
* Primary blocker identification
* Recommended next action
* Complete formatted final report

---

## Python Concepts Used

* Variables
* Data Types
* Input and Output
* Type Casting
* Arithmetic Operators
* Relational Operators
* Logical Operators
* Assignment Operators
* `if`, `elif`, `else`
* Nested Conditions
* `for` Loop
* `while` Loop
* `continue`
* Counters
* Accumulators
* Boolean Expressions
* f-Strings

---

## How to Run

Run the program using:

```bash
python main.py
```

or

```bash
python3 main.py
```

---

## Individual Contribution

**Name:** Kollu Venkata Sai

**GitHub Profile:** https://github.com/kolluvenkatasai143

**Repository URL:** https://github.com/kolluvenkatasai143/PrepTrack

**Role:** Python Developer

### My Main Contribution

* Developed the complete placement-performance analysis logic.
* Implemented score processing and placement-readiness evaluation.
* Added validation for attendance, project status, profile verification, and practice scores.
* Designed the final performance report.

### Features I Implemented

* Student profile collection
* Attendance validation
* Seven-day practice score analysis
* Pass/Fail counting
* Highest and Lowest score detection
* Average score calculation
* Placement readiness logic
* Primary blocker detection
* Final recommendation report

### Python Concepts I Used

* Variables
* Conditional Statements
* Loops
* Boolean Logic
* Counters
* Accumulators
* Input Validation
* f-Strings

### Most Difficult Logic

Implementing the placement-readiness decision while ensuring that only the first blocker is displayed as the primary reason for the student's status.

### Problem I Faced

Handling absent practice days while calculating the average score and maintaining accurate pass/fail counts.

### How I Solved It

I used the `continue` statement to skip absent days and maintained separate counters and accumulators so that only valid practice scores were included in the calculations.

---

## Team Directory (Team Lead Only)

| Member Name | GitHub Profile Link | PrepTrack Repository Link | Submission Status |
| ----------- | ------------------- | ------------------------- | ----------------- |
| Member 1    |                    |                            | Pending           |
| Member 2    |                     |                           | Pending           |
| Member 3    |                     |                           | Pending           |
| Member 4    |                     |                           | Pending           |
| Member 5    |                     |                           | Pending           |
| Member 6    |                     |                           | Pending           |
| Member 7    |                     |                           | Pending           |
| Member 8    |                     |                           | Pending           |

---

## Author

**Kollu Venkata Sai**

**Role:** Python Developer

**GitHub:** https://github.com/kolluvenkatasai143
