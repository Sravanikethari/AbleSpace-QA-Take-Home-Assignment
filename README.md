# AbleSpace QA Testing Project

## Project Overview

This project documents manual QA testing performed on the AbleSpace application in the staging environment. The testing focused on functional workflows, exploratory testing, defect identification, and browser and mobile compatibility.

**Application URL:** https://staging.ablespace.io  
**Environment:** Staging  
**Tester:** Sravani Kethari  
**Browsers Tested:** Brave Browser, Microsoft Edge  
**Mobile Viewport:** Android — 390 × 844  
**Testing Type:** Manual Functional, Exploratory, and Compatibility Testing

## Project Objectives

- Verify core goal creation and editing functionality.
- Test objective creation, editing, and search behaviour.
- Identify functional defects and UI inconsistencies.
- Evaluate browser compatibility and mobile responsiveness.
- Document defects with reproducible steps and supporting evidence.

## Testing Deliverables

| File | Description |
|---|---|
| `AbleSpace_Test_Cases.xlsx` | Detailed test cases, expected results, actual results, and statuses |
| `AbleSpace_Bug_Reports.xlsx` | Documented defects, severity, priority, reproduction steps, and evidence |
| `AbleSpace_Compatibility_Report.xlsx` | Browser compatibility, mobile responsiveness, and integration findings |
| `AbleSpace_Test_Summary.md` | Overall testing results, key findings, and conclusion |

## Test Results

A total of 8 detailed test cases were executed.

- **Passed:** 5
- **Failed:** 2
- **Edge Cases:** 1

**Pass rate:** 62.5% of all test cases, or 71.4% of cases classified as Pass or Fail.

## Key Findings

- A goal created using only a description did not appear until the page was refreshed.
- Adding an objective to an existing goal caused the goal to disappear and remain unavailable after refreshing and searching.
- Objectives added to a newly created goal were saved and displayed correctly.
- A potential objective-description duplication issue was observed.
- The Student 2 view displayed the title “Student 1” despite showing the correct data.
- AccomTracker displayed an authentication error.
- EIP System opened a blank page.
- The Student Profile page was difficult to view at the tested mobile viewport because content was cut off.

## Test Evidence

Screenshots and screen recordings are included as supporting evidence for the test cases and reported defects. Each evidence file should be linked to the relevant test case or bug ID.

### 1. Functional Test Evidence

Use this section for screenshots showing successful and unsuccessful test scenarios, including goal creation, editing, objective management, validation, and data visualisation.

| Test Case | Evidence | Observation |
|---|---|---|
| TC-01 | [Add screenshot link] | Goal appeared only after refreshing |
| TC-02 | [Add screenshot link] | Goal description updated successfully |
| TC-03 | [Add screenshot link] | New goal appeared after saving |
| TC-04 | [Add screenshot link] | Goal title updated successfully |
| TC-05 | [Add screenshot link] | Existing goal disappeared after adding an objective |
| TC-06 | [Add screenshot link] | Search did not retrieve the missing goal or objective |
| TC-07 | [Add screenshot link] | Objective appeared in the new goal's details |
| TC-08 | [Add screenshot link] | Two objectives appeared separately after saving |

### 2. Bug Evidence

| Bug ID | Issue | Evidence |
|---|---|---|
| BUG-01 | AccomTracker authentication failure | [View screenshot or recording](Evidence/BUG-01-AccomTracker-Authentication-Failed.mp4) |
| BUG-02 | EIP System blank page | [Add screenshot or recording link] |
| BUG-03 | Student 2 displayed with the title Student 1 | [View recording](Evidence/BUG-03-Student-2-Displays-Student-1.mp4) |

### 3. Compatibility Evidence

Add screenshots demonstrating:

- Brave Browser and Microsoft Edge behaviour.
- Mobile layout and content cut-off at 390 × 844.
- AccomTracker authentication failure.
- EIP System blank-page behaviour.

**Note:** iPad compatibility was not tested.

## Repository Structure

```text
ablespace-qa-testing/
├── README.md
├── AbleSpace_Test_Cases.xlsx
├── AbleSpace_Bug_Reports.xlsx
├── AbleSpace_Compatibility_Report.xlsx
├── AbleSpace_Test_Summary.md
└── Evidence/
    ├── README.md
    ├── screenshots/
    │   ├── TC-01-Goal-Visibility.png
    │   ├── BUG-01-AccomTracker-Error.png
    │   ├── BUG-02-IEP-System-Blank-Page.png
    │   └── BUG-03-Student-Label-Mismatch.png
    └── videos/
        ├── BUG-01-AccomTracker-Authentication-Failed.mp4
        └── BUG-03-Student-2-Displays-Student-1.mp4
```

*The filenames above are examples. Replace them with your actual uploaded filenames and paths.*

## Conclusion

This project demonstrates a structured manual QA workflow, including test planning, functional verification, defect reporting, compatibility testing, and evidence collection. The documented findings can help developers reproduce the observed issues and verify fixes during subsequent testing.

**Prepared by:** Sravani Kethari
