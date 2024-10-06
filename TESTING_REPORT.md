# Testing Report

## Method: isStrongPassword
| Test Case | Input           | Expected Output | Actual Output | Pass/Fail |
|-----------|-----------------|-----------------|---------------|-----------|
| TC1       | "P@ssw0rd"      | true            | true          | Pass      |
| TC2       | "password"      | false           | false         | Pass      |
| TC3       | "Password"      | false           | false         | Pass      |
| TC4       | "P@ssword"      | false           | false         | Pass      |
| TC5       | "P@ss1234"      | true            | true          | Pass      |

...

## Method: calculateExpression
| Test Case | Input            | Expected Output | Actual Output | Pass/Fail |
|-----------|------------------|-----------------|---------------|-----------|
| TC1       | "(10 + 5) * 2"   | 30.0            | 30.0          | Pass      |
| TC2       | "10 + 5 * 2"     | 20.0            | 20.0          | Pass      |
| TC3       | "100 / 5 + 20"   | 40.0            | 40.0          | Pass      |
| TC4       | "2 * (3 + 4)"    | 14.0            | 14.0          | Pass      |
| TC5       | "((1 + 2) * 3)"  | 9.0             | 9.0           | Pass      |
