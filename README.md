# AbleSpace QA Take-Home Assignment

## 1. Project Overview

This repository contains the manual QA testing deliverables for the AbleSpace staging application. Testing focused on goal creation and management, objective handling, data entry, graph functionality, defect identification, and compatibility testing.

| Detail | Information |
|---|---|
| Application | AbleSpace |
| Environment | Staging |
| Application URL | https://staging.ablespace.io |
| Tester | Sravani Kethari |
| Browsers Tested | Brave Browser, Microsoft Edge |
| Mobile Viewport | Android — 390 × 844 |
| Testing Approach | Manual Functional, Exploratory, and Compatibility Testing |

## 2. Repository Structure

```text
AbleSpace-QA-Take-Home-Assignment/
├── README.md
├── AbleSpace_Test_Summary.md
├── AbleSpace_Test_Cases.xlsx
├── AbleSpace_Bug_Reports.xlsx
├── AbleSpace_Compatibility_Report.xlsx
└── Evidence/
    ├── README.md
    ├── screenshots/
    │   ├── Testing by adding data in created goal.png
    │   ├── Changing chart type.png
    │   ├── Adding second Objective.png
    │   ├── Adding Objective.png
    │   ├── Adding one objective for existing file.png
    │   ├── Existing file added objective update successfull.png
    │   ├── Goal updated with two obj.png
    │   ├── Goal successful creation without goal tile.png
    │   ├── New goal creation without goal title.png
    │   └── Adding second Objective existing file.png
    └── videos/
        ├── BUG-01-AccomTracker-Authentication-Failed.mp4
        └── BUG-03-Student-2-Displays-Student-1.mp4
```

*Note: This is the intended structure. Ensure that the files are uploaded using these names and paths, or update the tree to match your actual repository.*

## 3. Project Objectives

- Verify goal creation, editing, and persistence.
- Test objective creation, updates, and display.
- Validate search behaviour and form validation.
- Verify data entry and graph functionality.
- Identify functional defects and UI inconsistencies.
- Evaluate browser compatibility, mobile responsiveness, and application integrations.
- Provide screenshots and screen recordings as supporting evidence.

## 4. Testing Deliverables

| Deliverable | File | Description |
|---|---|---|
| Test Summary | `AbleSpace_Test_Summary.md` | Overall results, key findings, and conclusion |
| Test Cases | `AbleSpace_Test_Cases.xlsx` | Preconditions, test data, steps, expected results, actual results, and status |
| Bug Reports | `AbleSpace_Bug_Reports.xlsx` | Defect descriptions, reproduction steps, severity, priority, and evidence |
| Compatibility Report | `AbleSpace_Compatibility_Report.xlsx` | Browser, mobile, and integration findings |
| Supporting Evidence | `Evidence/` | Screenshots and screen recordings from testing |

## 5. Test Results

A total of eight detailed test cases were executed.

| Status | Count |
|---|---:|
| Passed | 5 |
| Failed | 2 |
| Edge Cases | 1 |
| **Total** | **8** |

**Pass rate:** 62.5% of all test cases, or 71.4% of cases classified as Pass or Fail.

## 6. Key Findings

- A goal created using only a description did not appear immediately and became visible after refreshing the page.
- Adding an objective to an existing goal caused the goal to disappear and remain unavailable after refreshing and searching.
- Objectives added to a newly created goal were displayed separately after saving and reopening the goal.
- Empty goal submissions were prevented by validation.
- A potential objective-description duplication issue was observed when adding a second objective.
- The Student 2 view displayed the title “Student 1,” although the displayed data was correct.
- AccomTracker displayed an authentication failure.
- EIP System opened a blank page (`about:blank`).
- At the tested mobile viewport, some Student Profile content was cut off and difficult to view.

## 7. Screenshots and Test Evidence

The screenshots below document the observed application behaviour during functional and exploratory testing. displayed directly under its relevant heading.

### 7.1 Goal Creation Without a Title

**Screenshot:** `New goal creation without goal title.png`

**Add the screenshot below this heading.**

This screenshot documents the goal creation workflow using a description without a title.

![Goal creation without title](<img width="1920" height="966" alt="New goal creation without goal title" src="https://github.com/user-attachments/assets/feb9ec7f-e573-4182-9838-7cf670a00ea5" />
)

### 7.2 Goal Not Visible Immediately After Saving

**Screenshot:** `Goal successful creation without goal tile.png`

**Add the screenshot below this heading.**

The goal did not appear in the list immediately after saving and became visible after refreshing the page.

![Goal visibility after creation](Evidence/screenshots/Goal%20successful%20creation%20without%20goal%20tile.png)

### 7.3 Adding an Objective

**Screenshot:** `Adding Objective.png`

**Add the screenshot below this heading.**

This screenshot documents the workflow for adding an objective to a goal.

![Adding an objective](Evidence/screenshots/Adding%20Objective.png)

### 7.4 Adding a Second Objective

**Screenshot:** `Adding second Objective.png`

**Add the screenshot below this heading.**

This screenshot shows the process of adding a second objective.

![Adding a second objective](Evidence/screenshots/Adding%20second%20Objective.png)

### 7.5 Goal Updated with Two Objectives

**Screenshot:** `Goal updated with two obj.png`

**Add the screenshot below this heading.**

Both objectives appeared separately after saving and reopening the newly created goal.

![Goal updated with two objectives](Evidence/screenshots/Goal%20updated%20with%20two%20obj.png)

### 7.6 Adding an Objective to an Existing Goal

**Screenshot:** `Adding one objective for existing file.png`

**Add the screenshot below this heading.**

This screenshot documents the attempt to add an objective to a goal that already existed.

![Adding an objective to an existing goal](Evidence/screenshots/Adding%20one%20objective%20for%20existing%20file.png)

### 7.7 Adding a Second Objective to an Existing Goal

**Screenshot:** `Adding second Objective existing file.png`

**Add the screenshot below this heading.**

This screenshot supports the investigation of objective management on an existing goal.

![Adding a second objective to an existing goal](Evidence/screenshots/Adding%20second%20Objective%20existing%20file.png)

### 7.8 Existing Goal Update Confirmation

**Screenshot:** `Existing file added objective update successfull.png`

**Add the screenshot below this heading.**

This screenshot documents the update confirmation observed during the existing-goal workflow.

![Existing goal update confirmation](Evidence/screenshots/Existing%20file%20added%20objective%20update%20successfull.png)

### 7.9 Data Entry in a Created Goal

**Screenshot:** `Testing by adding data in created goal.png`

**Add the screenshot below this heading.**

This screenshot demonstrates data entry for a created goal and supports the test of recording and displaying goal data.

![Data entry in a created goal](Evidence/screenshots/Testing%20by%20adding%20data%20in%20created%20goal.png)

### 7.10 Changing the Chart Type

**Screenshot:** `Changing chart type.png`

**Add the screenshot below this heading.**

This screenshot documents the available graph options and the chart-type selection workflow.

![Changing chart type](Evidence/screenshots/Changing%20chart%20type.png)

## 8. Bug Reports and Screen Recording Evidence

Detailed reproduction steps, expected results, actual results, severity, and priority are documented in `AbleSpace_Bug_Reports.xlsx`.

### BUG-01: AccomTracker Authentication Failure

**Evidence file:** `BUG-01-AccomTracker-Authentication-Failed.mp4`

**Add the screen recording link below this heading.**

[View AccomTracker authentication failure recording](Evidence/videos/BUG-01-AccomTracker-Authentication-Failed.mp4)

**Observation:** AccomTracker displayed “Authentication Failed” when the application link was opened.

### BUG-02: EIP System Blank Page

**Evidence:** Add the relevant screenshot or recording when uploaded.

**Observation:** EIP System opened a blank page (`about:blank`), indicating a potential integration or configuration issue.

### BUG-03: Incorrect Student Label

**Evidence file:** `BUG-03-Student-2-Displays-Student-1.mp4`

**Add the screen recording link below this heading.**

[View Student label mismatch recording](Evidence/videos/BUG-03-Student-2-Displays-Student-1.mp4)

**Observation:** The Student 2 view displayed the title “Student 1,” although the displayed data was correct.

## 9. Compatibility Summary

Compatibility testing was performed using Brave Browser and Microsoft Edge, along with an Android mobile viewport of 390 × 844.

- **Brave Browser:** Desktop workflows tested.
- **Microsoft Edge:** Desktop workflows tested.
- **Android mobile viewport:** Student Profile content was difficult to view because some text, tabs, and content were cut off.
- **AccomTracker:** Authentication failure observed.
- **EIP System:** Blank page observed.
- **iPad:** Not tested.

Refer to `AbleSpace_Compatibility_Report.xlsx` for the detailed compatibility findings.

## 10. Conclusion

This project demonstrates a structured manual QA process covering functional testing, exploratory testing, defect reporting, and compatibility testing.

The Excel workbooks contain the detailed test records, while the screenshots and screen recordings provide supporting evidence of the observed behaviours. The identified issues should be investigated and retested after fixes are applied.

**Prepared by:** Sravani Kethari
