# AbleSpace — Test Summary Report

**Tester:** Sravani Kethari  
**Application:** AbleSpace  
**Environment:** Staging  
**URL:** https://staging.ablespace.io  
**Testing Type:** Manual Functional, Exploratory, and Compatibility Testing  
**Browsers Tested:** Brave Browser and Microsoft Edge  
**Mobile Viewport:** Android — 390 × 844  
**Date:** 22 October 2026

## 1. Objective

The objective was to evaluate AbleSpace's core functionality, usability, and browser compatibility, identify defects, and document the observed results.

## 2. Testing Summary

A total of 8 test cases were executed.

- **Passed:** 5
- **Failed:** 2
- **Edge Cases:** 1
- **Pass Rate:** 62.5% of all test cases, or 71.4% of cases classified as Pass or Fail.

## 3. Key Findings

- Goal creation and editing generally worked as expected.
- A goal created using only a description did not appear until the page was refreshed.
- Adding an objective to an existing goal caused the goal to disappear and remain unavailable after refreshing and searching.
- Objectives added to a newly created goal were saved and displayed correctly.
- Empty goal submissions were prevented by validation.
- A potential objective-description duplication issue was observed when adding a second objective.
- The Student 2 view displayed the title “Student 1,” although the displayed data was correct.

## 4. Compatibility and Integration Findings

Testing was performed using Brave Browser and Microsoft Edge. At the Android mobile viewport of 390 × 844, the Student Profile page was difficult to view because some text, tabs, and content were cut off.

Of the four application links tested, two opened successfully. AccomTracker displayed “Authentication Failed,” while EIP System opened a blank page (`about:blank`). These issues require further investigation.

**iPad testing was not performed.**

## 5. Conclusion

The core goal-management functionality worked in several scenarios, but issues affecting existing goals, student-view labelling, mobile responsiveness, and application integrations require attention. The findings are documented in the test cases, bug reports, and compatibility report.

Further testing is recommended after the identified issues are addressed.
