# Library Guide · Member Services Desk at a Public Library

How to use this prompt library, in one page.  
**Owner:** Muna Alharby · **Version:** v1 · **Date:** 2026_10_15

## 1. What is in the library

| Folder / file | What it holds |
|---|---|
| `library_index.md` | The list of all templates, blocks and rules, with their versions and status |
| `templates/` | 5 approved templates, one per task |
| `blocks/` | Shared text pasted into templates: the Library Facts and the request categories |
| `rules/` | The 5 responsible-use rules every agent follows |
| `Test_Results_Report.pdf` | The three-test scores and one screenshot for each template |
| `_archive/` | Old versions, kept for reference only. Never use them |

## 2. How to use a template

1. **Choose** the template for your task in `library_index.md`. Use only templates marked Approved.
2. **Copy** the part of the file from `ROLE:` to the end of `EXPECTATION`. Do not copy the variables table, the example or the change log.
3. **Mask the input first.** Replace every name, membership number and phone number with a code such as Member-1, Membership-X or Phone-1 (Rule 1).
4. **Fill the variables:**
   - Replace `[LIBRARY_FACTS]` or `[CATEGORIES]` with the text of the current block from `blocks/`.
   - Replace the input variable (`[INQUIRY]`, `[LETTER]`, `[REQUEST]`, `[DRAFT]` or `[DUE_DATE]`) with the masked text.
   - Set `[LANGUAGE]`, `[TONE]` and `[MAX_WORDS]`, or leave the defaults from the variables table.
5. **Never remove or change the RULES.** They are fixed safety rules.
6. **Run** the prompt in an AI tool your organization approves.

## 3. How to check the output

Before anything is sent, check the output with the verification checklist. Every line must be yes:

| Check | Yes / no |
|---|---|
| Every fact is in the current Facts block (or is marked NOT IN FACTS) | ☐ |
| Numbers, dates and names match the source exactly | ☐ |
| No promised date and no "I did this" | ☐ |
| No personal data repeated, only codes | ☐ |
| Every question is answered or flagged, and the wording reads naturally | ☐ |

Then a named librarian approves the reply and deletes the CHECK section before sending (Rules 2 and 5). If any line is no, do not send: fix the input or report the problem to the template owner.

## 4. Who owns what

| File | Owner | When it changes |
|---|---|---|
| Templates | Muna Alharby | After a failed check or a new need; save a new version, test it with the three tests and move the old one to `_archive/` |
| LB-Facts block | Muna Alharby | Within one working day of an official notice that changes a fact (Rule 4) |
| LB-Categories block | Muna Alharby | When the request categories change; test LB-Classify-Request again |
| LB-Rules | Muna Alharby | When the desk's responsible-use policy changes |

New versions follow the name pattern `LB-Task-Object-vN_yyyy_mm_dd`, and the index is updated at the same time.