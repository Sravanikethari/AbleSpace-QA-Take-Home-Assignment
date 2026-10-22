# AbleSpace-QA-Take-Home-Assignment
Writing      Manual QA testing project for Ablespace, covering exploratory testing, detailed test cases, bug reports, and cross-browser compatibility testing.


**Tester:** Sravani Kethari  
**Date:** 22 October 2026  
**Application:** [https://staging.ablespace.io](https://staging.ablespace.io)  
**Submission Type:** GitHub Repository

---

## Overview

This repository contains the complete QA deliverables for the AbleSpace IEP Goal Tracking App take-home assignment.

---

## Repository Structure

```
ablespace-qa-take-home/
│
├── README.md
│
├── 01-Test-Cases/
│   └── AbleSpace_Test_Cases.xlsx
│
├── 02-Bug-Reports/
│   └── AbleSpace_Bug_Reports.xlsx
│
├── 03-Compatibility-Report/
│   └── AbleSpace_Compatibility_Report.xlsx
│
├── 04-Test-Summary/
│   └── TEST_SUMMARY.md
│
└── evidence/                    # Optional - screenshots & videos
    ├── screenshots/
    └── videos/
```

---

## Deliverables

| Section | Description                        | File |
|---------|------------------------------------|------|
| **3**   | Detailed Test Cases                | `01-Test-Cases/AbleSpace_Test_Cases.xlsx` |
| **4**   | Bug Reports with Evidence          | `02-Bug-Reports/AbleSpace_Bug_Reports.xlsx` |
| **5**   | Cross-browser & Responsive Report  | `03-Compatibility-Report/AbleSpace_Compatibility_Report.xlsx` |
| **6**   | Test Summary                       | `04-Test-Summary/TEST_SUMMARY.md` |

---

## Testing Environment

- **Desktop Browsers:** Brave (Chromium) and Microsoft Edge
- **Mobile:** Real Android device
- **Not Tested:** iPad (Mini & Pro), Firefox

---

## How to Review

1. Start with **`04-Test-Summary/TEST_SUMMARY.md`** for a quick overview of what was tested and the main findings.
2. Open the Excel files for detailed test cases, bug reports, and compatibility results.
3. Check the `evidence` folder (if included) for screenshots and video recordings.

---

## Notes

- All Excel files are professionally formatted and ready for review.
- Critical bugs related to Accommodation Tracker authentication and IEP System configuration were found on both Brave and Edge.
- Mobile testing showed mostly good usability with a few content truncation issues.
