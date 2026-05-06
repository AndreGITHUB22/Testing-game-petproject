# Defect Report

**Defect ID:** Presc_bu7g_FN_01

**Summary:** “Add More Medicine” title remains visible when “Medicine” text field is not empty

**Defect type:** Functional

**Priority:** Medium

**Severity:** Medium

**Environment:** Windows 10 Home, Google Chrome ver.116.0.5845.187

## Precondition
“Prescription” page is opened

## Steps to Reproduce

| N | Steps to reproduce | Test data |
|---|---|---|
| 1 | Locate “Medicine” text field |  |
| 2 | Keep “Medicine” text field empty |  |
| 3 | Observe “Add More Medicine” title below the field |  |
| 4 | Type test data in “Medicine” text field | Ibuprom |
| 5 | Observe “Add More Medicine” title below the field |  |
| 6 | Clear “Medicine” text field |  |
| 7 | Observe “Add More Medicine” title below the field |  |

## Actual Result
Title does not disappear when “Medicine” field is not empty.

## Expected Result
“Add More Medicine” title is displayed when the “Medicine” field is empty and hidden when the field contains text.

## Attachments
None
