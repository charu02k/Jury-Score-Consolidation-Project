# 🏆 Jury Score Consolidation Using Excel VLOOKUP

This project demonstrates how Excel’s **VLOOKUP** function can be used to consolidate data from multiple sheets and create an automated scoring and ranking system. The dataset represents a competition where three jury panels evaluated multiple teams across different parameters.

---

This project showcases how Excel’s VLOOKUP function can be used to merge data from multiple sheets and create an automated scoring and ranking system. The dataset represents a hackathon-style event where three juries evaluated multiple teams across different criteria.

📌 **Project Overview**

The workbook contains:

Three jury sheets (Jury1, Jury2, Jury3) listing:

Team Name

Team Strength

Team Lead

Multiple evaluation parameters

Individual score components

A main_Sheet that consolidates all jury scores using Excel formulas.

🔍 **What VLOOKUP Is Used For**

VLOOKUP is applied in main_Sheet to automatically:

Fetch each Jury’s total score for every team

Avoid manual copying from individual jury sheets

Ensure data consistency even when team order changes

Build a unified scoring system that updates whenever jury sheets are modified

📊 **Key Features**
✔️ Automated Score Consolidation

VLOOKUP retrieves:

Jury 1 Total Score

Jury 2 Total Score

Jury 3 Total Score

These values are then used to compute:

Grand Total (sum of all jury scores)

Final Rank (sorted based on total score)

✔️ **Error-Free Data Retrieval**

To handle missing or unmatched records, the project uses:

IFERROR(VLOOKUP(...), "") to keep the sheet clean

✔️ **Dynamic Ranking**

As jury scores change, the ranking updates automatically using:

RANK() or RANK.EQ()

🎯 **Outcome**

This project demonstrates how Excel can be used to:

Combine multiple datasets

Automate score calculations

Simplify judging workflows

Produce ranked results with zero manual intervention

It’s a practical example of using Excel functions for real-world evaluation and decision-making systems.

