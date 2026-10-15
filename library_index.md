# Library Index · Member Services Desk at a Public Library

Prompt library for the Member Services Desk (Path B · Scenario B5 · Prefix LB).  
**Owner:** Muna Alharby · **Version:** v1 · **Date:** 2026_10_15

## Templates

| # | Template | Task | Variables | Version | Status |
|---|---|---|---|---|---|
| 1 | [LB-Answer-Question](templates/LB-Answer-Question-v1_2026_10_15.md) | Answer a member's question | [INQUIRY] [LANGUAGE] [TONE] [MAX_WORDS] [LIBRARY_FACTS] | v1 | Approved |
| 2 | [LB-Summarize-Letter](templates/LB-Summarize-Letter-v1_2026_10_15.md) | Summary of a member's letter | [LETTER] [LANGUAGE] [MAX_WORDS] | v1 | Approved |
| 3 | [LB-Classify-Request](templates/LB-Classify-Request-v1_2026_10_15.md) | Sort member requests | [REQUEST] [CATEGORIES] [LANGUAGE] | v1 | Approved |
| 4 | [LB-Rewrite-Note](templates/LB-Rewrite-Note-v1_2026_10_15.md) | Friendlier staff note | [DRAFT] [LANGUAGE] [TONE] [MAX_WORDS] | v1 | Approved |
| 5 | [LB-Draft-Reminder](templates/LB-Draft-Reminder-v1_2026_10_15.md) | Due-date reminder | [DUE_DATE] [LANGUAGE] [TONE] [MAX_WORDS] [LIBRARY_FACTS] | v1 | Approved |

Test scores and screenshots: [Test_Results_Report.pdf](Test_Results_Report.pdf)

## Shared blocks

| Block | What it holds | Used by | Version | Status |
|---|---|---|---|---|
| [LB-Facts](blocks/LB-Facts-v1_2026_10_15.md) | The 7 Library Facts | LB-Answer-Question, LB-Draft-Reminder | v1 | Current |
| [LB-Categories](blocks/LB-Categories-v1_2026_10_15.md) | The 5 request categories with meanings | LB-Classify-Request | v1 | Current |

## Rules

| File | What it holds | Version | Status |
|---|---|---|---|
| [LB-Rules](rules/LB-Rules-v1_2026_10_15.md) | The 5 responsible-use rules (data, verification, fairness, policy, human decision), adapted from Lab 4 | v1 | Current |

## [LANGUAGE] values

Every template that writes text for a person uses the same five values.

| Value | Meaning |
|---|---|
| Arabic | Answer in Arabic only |
| English | Answer in English only |
| Automated (default) | Reply in the main language of the input |
| Bilingual | Two separate versions: Arabic, then English |
| Mixed | One reply that merges Arabic and English |

## Change log

| Version | Date | Change |
|---|---|---|
| v1 | 2026_10_15 | First version: 5 templates, 2 shared blocks, 1 rules file |