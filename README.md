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

<img width="1920" height="966" alt="Image" src="https://github.com/user-attachments/assets/73f1c8df-c06b-4a53-9a4f-7af4ebe2f1c7" />

### 7.2 Goal Not Visible Immediately After Saving


**Add the screenshot below this heading.**

The goal did not appear in the list immediately after saving and became visible after refreshing the page.

<img width="1920" height="974" alt="Image" src="https://github.com/user-attachments/assets/2eb26879-7178-44a6-acad-1eb2580b0e8e" />

### 7.3 Adding an Objective


**Add the screenshot below this heading.**

This screenshot documents the workflow for adding an objective to a goal.

<img width="1920" height="972" alt="Image" src="https://github.com/user-attachments/assets/b71bb349-5318-4156-98fc-48e1bb37c41f" />

### 7.4 Adding a Second Objective


**Add the screenshot below this heading.**

This screenshot shows the process of adding a second objective.

<img width="1920" height="955" alt="Image" src="https://github.com/user-attachments/assets/341679c1-249b-4ecf-abb4-86543b3ae6cf" />

### 7.5 Goal Updated with Two Objectives


**Add the screenshot below this heading.**

Both objectives appeared separately after saving and reopening the newly created goal.

<img width="1920" height="966" alt="Goal updated with two obj" src="https://github.com/user-attachments/assets/3f2033e9-a258-4677-b595-61f7aafacad9" />


### 7.6 Adding an Objective to an Existing Goal



**Add the screenshot below this heading.**

This screenshot documents the attempt to add an objective to a goal that already existed.

<img width="1920" height="967" alt="Image" src="https://github.com/user-attachments/assets/d2b9ce28-f8e4-4e84-8663-cc64f4b2bc38" />

### 7.7 Adding a Second Objective to an Existing Goal


**Add the screenshot below this heading.**

This screenshot supports the investigation of objective management on an existing goal.

<img width="1920" height="960" alt="Image" src="https://github.com/user-attachments/assets/56491064-c894-4879-8ba1-2dc6d9cddfbe" />

### 7.8 Existing Goal Update Confirmation


**Add the screenshot below this heading.**

This screenshot documents the update confirmation observed during the existing-goal workflow.

<img width="1920" height="968" alt="Image" src="https://github.com/user-attachments/assets/221d8d7f-849f-4845-950c-74026430495a" />

### 7.9 Data Entry in a Created Goal



**Add the screenshot below this heading.**

This screenshot demonstrates data entry for a created goal and supports the test of recording and displaying goal data.

<img width="1920" height="970" alt="Image" src="https://github.com/user-attachments/assets/50455449-b047-4754-bd50-a9ca664547bb" />

### 7.10 Changing the Chart Type


**Add the screenshot below this heading.**

This screenshot documents the available graph options and the chart-type selection workflow.

<img width="1920" height="968" alt="Image" src="https://github.com/user-attachments/assets/e29677f7-a827-49cf-a886-c88588899bf6" />

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
