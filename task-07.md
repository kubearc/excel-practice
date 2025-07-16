

````markdown
# ✅ Excel Task: Student Eligibility Checker.

## 🔧 Task Description

This Excel task helps you understand how to use logical functions like `AND` and `OR` to check multiple conditions and return `TRUE` or `FALSE` based on student eligibility criteria.

---

## 📁 Given Data

| Student Name | Marks (%) | Attendance (%) | Eligible (AND) | Eligible (OR) |
|--------------|-----------|----------------|----------------|---------------|
| Aditi        | 85        | 92             |                |               |
| Rohan        | 65        | 75             |                |               |
| Simran       | 70        | 68             |                |               |
| Arjun        | 45        | 85             |                |               |

---

## ✅ Solution Steps

1. In **column D**, use the `AND` function to check if both conditions are met:
   - Marks ≥ 60
   - Attendance ≥ 75

   📍 Formula in **D2**:
   ```excel
   =AND(B2>=60, C2>=75)
````

2. In **column E**, use the `OR` function to check if at least one condition is met:

   * Marks ≥ 60
   * Attendance ≥ 75

   📍 Formula in **E2**:

   ```excel
   =OR(B2>=60, C2>=75)
   ```

3. **Drag both formulas** from row 2 down to row 5.

---

## ✅ Final Output Example

| Student Name | Marks (%) | Attendance (%) | Eligible (AND) | Eligible (OR) |
| ------------ | --------- | -------------- | -------------- | ------------- |
| Aditi        | 85        | 92             | TRUE           | TRUE          |
| Rohan        | 65        | 75             | TRUE           | TRUE          |
| Simran       | 70        | 68             | FALSE          | TRUE          |
| Arjun        | 45        | 85             | FALSE          | TRUE          |

---

## 🧠 Learning Recap

* ✅ `AND` returns `TRUE` only when **all** conditions are met.
* ✅ `OR` returns `TRUE` if **any one** condition is met.
* ✅ Logical functions help evaluate complex rules in Excel quickly.

---

> 🧪 Try changing the eligibility criteria or the student data to test different logical outcomes!


