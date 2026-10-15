# PE_Library_Muna

Prompt library for a Member Services Desk at a Public Library: five approved, tested prompt templates built from structured RACE prompts.

## Path and scenario

- **Path:** B (Guided path)
- **Scenario:** B5 · Member Services Desk at a Public Library
- **Prefix:** LB
- **Library folder:** [PE_Library_Muna](PE_Library_Muna/)

All data in this repository is invented. No real organization, person, number or document is used.

## The 10 tasks

The 5 tasks built in this library are marked ✅.

| No. | Task | Goal | Built | Template |
|---|---|---|---|---|
| 1 | Answer a member's question | Write a short, polite answer to a member's question using only the Library Facts. | ✅ | LB-Answer-Question |
| 2 | Summary of a member's letter | Summarize a long member letter in three lines for the librarian. | ✅ | LB-Summarize-Letter |
| 3 | Sort member requests | Label each request as Borrowing, Renewal, Membership, Events or Other. | ✅ | LB-Classify-Request |
| 4 | Friendlier staff note | Rewrite a short, blunt staff note as a friendly message to a member. | ✅ | LB-Rewrite-Note |
| 5 | Bilingual library notice | Translate an approved library notice between Arabic and English without changing any date or fact. | | |
| 6 | Due-date reminder | Write a reminder that a loan is due soon and how to renew it. | ✅ | LB-Draft-Reminder |
| 7 | Reading event announcement | Write a short announcement of a reading event with the date, time and place. | | |
| 8 | Mask member details | Replace names, membership numbers and phone numbers in a message with codes before it goes to an AI tool. | | |
| 9 | New member guide | Turn five common questions and their facts into a short FAQ list for new members. | | |
| 10 | Complaint handoff note | Write a short note for the head librarian when a complaint about a staff member needs a person's decision. | | |

## What is in the library

| File | What it is |
|---|---|
| `library_index.md` | Table of the 5 templates, shared blocks, rules and [LANGUAGE] values |
| `library_guide.md` | How to use the library, in one page |
| `Test_Results_Report.pdf` | Three-test scores and one screenshot per template |
| `blocks/` | LB-Facts (7 Library Facts) and LB-Categories (5 request categories) |
| `templates/` | The 5 approved templates |
| `rules/` | LB-Rules: the 5 responsible-use rules |

## Training Program
This project was completed as part of the Prompt Engineering and Responsible AI Use training program at SDAIA Academy, under the supervision of Abdullah Khalid Alshahrani. 

The project demonstrates the practical application of prompt engineering and responsible AI use — building a clean, approved prompt library through structured RACE prompts, reusable templates with variables and fixed output formats, safe handling of sensitive data, verification and responsible-use rules, and a documented three-test quality report.

Official SDAIA Academy GitHub:
https://github.com/SDAIAAcademy