# PRODIGY_WD_01 - Calculator Test Cases

## 📌 Detailed Test Cases

| **TestID**  | **Test Description**                       | **Preconditions**    | **Test Steps**          | **Expected Result**              | **Actual Result** | **Status** |
|-----------|--------------------------------|-------------------|-----------------------|-----------------------------|----------------|---------|
| TC_ADD_01 | Add two positive integers   | Calculator open   | Enter `5 + 3 =`     | Display shows `8`                | —              | —      |
| TC_ADD_02 | Add positive and negative numbers | Calculator open   | Enter `7 + (-2) =`  | Display shows `5`                | —              | —      |
| TC_SUB_01 | Subtract two numbers                  | Calculator open   | Enter `10 - 4 =`      | Display shows `6`                | —              | —      |
| TC_DIV_01 | Divide with decimals               | Calculator open   | Enter `7 ÷ 2 =`       | Display shows `3.5`             | —              | —      |
| TC_DIV_02 | Division by zero                 | Calculator open   | Enter `9 ÷ 0 =`       | Display shows `Error`            | —              | —      |
| TC_BODMAS_01 | Verify BODMAS precedence           | Calculator open   | Enter `2 + 3 × 4 =`  | Display shows `14`             | —              | —      |

### ❌ Invalid Input Test Cases

| **TestID**  | **Test Description**                   | **Preconditions**    | **Test Steps**          | **Expected Result**              | **Actual Result** | **Status** |
|-----------|------------------------------------|-------------------|-----------------------|-----------------------------|----------------|---------|
| TC_INV_01 | Non-numeric input handling     | Calculator open   | Enter `A + 5 =`     | Display shows `Error` or ignores input | —              | —      |
| TC_INV_02 | Multiple operators consecutively       | Calculator open   | Enter `5 ++ 3 =`  | Display shows `Error` or ignores extra operator | —              | —      |

---

