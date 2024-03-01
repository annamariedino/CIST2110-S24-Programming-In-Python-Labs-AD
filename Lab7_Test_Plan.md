## 1. Calculate rectangle area () function

| Test Case ID | Test Case Description | Test Data | Expected Result | Actual Result | Pass/Fail | If Fail, Why? |
|--------------|-----------------------|-----------|-----------------|---------------|-----------|---------------|
001 | calculate_rectangle_area - Test with positive numbers | 3, 4 | 12 | 12 | PASS | N/A |
002 | calculate_rectangle_area - Test with positive numbers | 5, 5 | 25 | 25 | PASS | N/A |
003 | calculate_rectangle_area - Test for zero | 0, 0 | 0 | 0 | PASS | N/A |
004 | calculate_rectangle_area - Test with positive numbers | 10, 20 | 200| 200 | PASS | N/A |

## 2. Calculate_hypotenus function
| Test Case ID | Test Case Description | Test Data | Expected Result | Actual Result | Pass/Fail | If Fail, Why? |
|--------------|-----------------------|-----------|-----------------|---------------|-----------|---------------|
001 | calculate_hypotenuse - Test with positive numbers | 3, 4 | 5 | 5 | PASS | N/A |
002 | calculate_hypotenuse - Test with positive numbers | 5, 12 | 13 | 16.401219466856727 | FAIL | a**3 is causing an incorrect calcualtion
003 | calculate_hypotenuse - Test with positive numbers (bugfix 002) | 5, 12 | 13 | 13 | PASS | N/A |
004 | calculate_hypotenuse - Test with positive numbers | 7, 24 | 25 | 25 | PASS | N/A |
005 | calculate_hypotenuse - Test with positive numbers | 8, 15 | 17 | 17 | PASS | N/A |

## 3. is_even function
| Test Case ID | Test Case Description | Test Data | Expected Result | Actual Result | Pass/Fail | If Fail, Why? |
|--------------|-----------------------|-----------|-----------------|---------------|-----------|---------------|
001 | is_even - Test with positive numbers | 2 | True | True | PASS | N/A
002 | is_even - Test with positive numbers | 7 | True | True | PASS | N/A
003 | is_even - Test with positive numbers | 0 | True | True | PASS | N/A
004 | is_even - Test with positive numbers | 11 | True | True | PASS | N/A

## 4. find_max function
| Test Case ID | Test Case Description | Test Data | Expected Result | Actual Result | Pass/Fail | If Fail, Why? |
|--------------|-----------------------|-----------|-----------------|---------------|-----------|---------------|
001 | find_maximum - Test with positive numbers | 3, 4 | 4 | 4 | PASS | N/A |


## 5. grade_calculator function
| Test Case ID | Test Case Description | Test Data | Expected Result | Actual Result | Pass/Fail | If Fail, Why? |
|--------------|-----------------------|-----------|-----------------|---------------|-----------|---------------|
001 | grade_calculator - Test with positive numbers | 90 | A | A | PASS | N/A |
002 | grade_calculator - Test with out of range upper bound | 105 | Invalid Input | A | FAIL | No upper bound, need to add > 100
003 | grade_calculator - Test with out of range upper bound (bugfix 002) | 105 | Invalid Input | Invalid Input | PASS | N/A


