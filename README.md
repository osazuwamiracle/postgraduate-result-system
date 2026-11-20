# Postgraduate Result Processing System

## Overview
An automated system for processing postgraduate (M.Sc.) examination results. It computes GPA, CGPA, classifies degrees, and generates transcripts — reducing manual errors in result computation.

Built as part of my M.Sc. preparation in Computer Science.

## Features
- Student record management (Reg No, Name, Programme, Session)
- Course registration with credit units and grades
- Automatic GPA calculation per semester
- Automatic CGPA calculation across semesters
- Degree classification: Distinction, Merit, Pass, Fail
- Transcript generation
- CSV export for departmental records

## Grading System
| Grade | Score | Grade Point |
| --- | --- | --- |
| A | 70 - 100 | 5.0 |
| B | 60 - 69 | 4.0 |
| C | 50 - 59 | 3.0 |
| D | 45 - 49 | 2.0 |
| E | 40 - 44 | 1.0 |
| F | 0 - 39 | 0.0 |

## Classification
- CGPA 4.50 - 5.00 = Distinction
- CGPA 3.50 - 4.49 = Merit / Upper Credit
- CGPA 2.50 - 3.49 = Lower Credit
- CGPA 1.00 - 2.49 = Pass
- CGPA Below 1.00 = Fail

## How To Run
```bash
pip install -r requirements.txt
python result_system.py
