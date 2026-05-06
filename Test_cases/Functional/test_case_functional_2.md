# Test Case

**Test case ID:** Presc.form.FN.02

**Summary:** Verify saving changes function

**Test case type:** Functional

**Priority:** High

## Precondition
“Prescription” page is opened

## Test Steps

| N | Test step | Test data | Expected result |
|---|---|---|---|
| 1 | Enter valid data in the “Disease” text field | Flu | Data is entered into the field and displayed |
| 2 | Enter valid data in the “Symptoms” text field | Fever | Data is entered into the field and displayed |
| 3 | Enter valid data in the “Medicine” text field | Ibuprom | Data is entered into the field and displayed |
| 4 | Enter valid data in the “Procedure to use medicine” text field | 2 times per day | Data is entered into the field and displayed |
| 5 | Enter valid data in the “Feedback” text field | Good | Data is entered into the field and displayed |
| 6 | Enter valid data in the “Signature” text field | Andrew M. | Data is entered into the field and displayed |
| 7 | Press “Save changes” button |  | The button becomes inactive, input fields become read-only, loading screen appears |
| 8 | Wait until loading end |  | User is redirected to “Main” page |
| 9 | Click on “Prescriptions” title in top of page |  | “Prescription” page is opened, created prescription is displayed |

## Post Condition
Data saved on “Prescription” page

## Additional Information

- **Designer:** Andrii Kolpakov
- **Status:** Pass
- **Created date:** 20.04.2026
