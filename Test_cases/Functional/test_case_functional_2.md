# Test Case

**Test case ID:** TC.FN.02

**Summary:** Verify that player can change and save vehicle color

**Test case type:** Functional

**Priority:** Medium

## Precondition
Game is opened <br>
Vehicle customization menu is opened

## Test Steps

| N | Test step | Test data | Expected result |
|---|---|---|---|
| 1 | Press "Customize" button|-| List of available vehicle colors appears , "Customize" button disappears |
| 2 | Press "Down" | - | Vehicle changed color |
| 3 | Press "Confirm" button | - | Confirmation sound is  played |
| 4 | Press "Back" button | - | Chosen vehicle color remains  , List of available vehicle colors disappears  |
| 5 | Press "Back" button | - | Changes are saved , vehicle exits from garage, control returns to player |

## Post Condition
Selected vehicle color is saved

## Additional Information

- **Designer:** Andrii Kolpakov
- **Status:** Pass
- **Created date:** 06.05.2026
