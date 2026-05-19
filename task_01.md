# PRODIGY_ST_01 - Calculator Test Cases

| **Test ID**   | **Test Description**                  | **Preconditions** | **Test Steps**             | **Expected Result** | **Actual Result** | **Status** |
|---------------|---------------------------------------|------------------|----------------------------|---------------------|------------------|------------|
| TC_ADD_01     | Add two positive integers             | Calculator open  | Enter `5 + 3 =`            | Display shows `8`   | 8                | Pass       |
| TC_ADD_02     | Add positive and negative numbers     | Calculator open  | Enter `7 + (-2) =`         | Display shows `5`   | 5                | Pass       |
| TC_SUB_01     | Subtract two numbers                  | Calculator open  | Enter `10 - 4 =`           | Display shows `6`   | 6                | Pass       |
| TC_MUL_01     | Multiply decimals                     | Calculator open  | Enter `2.5 × 4 =`          | Display shows `10`  | 10               | Pass       |
| TC_DIV_01     | Divide with decimals                  | Calculator open  | Enter `7 ÷ 2 =`            | Display shows `3.5` | 3.5              | Pass       |
| TC_BODMAS_01  | Verify BODMAS precedence              | Calculator open  | Enter `2 + 3 × 4 =`        | Display shows `14`  | 14               | Pass       |
| TC_DIV_02     | Division by zero                      | Calculator open  | Enter `9 ÷ 0 =`            | Display shows Error | Error            | Pass       |
| TC_INV_01     | Non-numeric input handling            | Calculator open  | Enter `A + 5 =`            | Display shows Error | Error            | Pass       |
| TC_INV_02     | Multiple operators consecutively      | Calculator open  | Enter `5 ++ 3 =`           | Display shows Error | Error            | Pass       |
| TC_INV_03     | Invalid decimal format                | Calculator open  | Enter `5..2 + 3 =`         | Display shows Error | Error            | Pass       |
| TC_INV_04     | Empty input                           | Calculator open  | Press `=` without numbers  | Display shows Error | Error            | Pass       |
