
# 📘 Excel Task: Student Performance Sheet

## 📌 Task Objective

Create a student performance tracking sheet that calculates total marks, average, and pass/fail status using formulas and formatting tools in Excel.

---

## 🧾 Columns Setup

In row 1, enter the following headers:

| A1           | B1        | C1        | D1        | E1        | F1     | G1      | H1     |
|--------------|-----------|-----------|-----------|-----------|--------|---------|--------|
| Student Name | Subject 1 | Subject 2 | Subject 3 | Subject 4 | Total  | Average | Status |

---

## ✍️ Sample Data

Enter this sample data starting from row 2:

| Student Name | Subject 1 | Subject 2 | Subject 3 | Subject 4 |
|--------------|-----------|-----------|-----------|-----------|
| John Doe     | 80        | 70        | 90        | 85        |
| Jane Smith   | 85        | 95        | 78        | 88        |
| Mike Johnson | 60        | 58        | 74        | 82        |

---

## ➕ Step 1: Calculate Total Marks

In **column F (Total)**, calculate the total marks for each student.

Formula in **F2**:
```excel
=SUM(B2:E2)
```
📌 Drag this formula down from F2 to apply it to other rows.

---

## ➗ Step 2: Calculate Average Marks

In **column G (Average)**, calculate the average of the marks.

Formula in **G2**:
```excel
=AVERAGE(B2:E2)
```
📌 Drag down from G2 to apply the formula for each student.

---

## ✔️ Step 3: Determine Status (Pass/Fail)

In **column H (Status)**, determine whether a student has passed (average ≥ 60) or failed.

Formula in **H2**:
```excel
=IF(G2>=60, "Pass", "Fail")
```
📌 Drag this formula down to complete the column.

---

## 🖌️ Step 4: Format the Sheet

1. **Bold Headers**:  
   Select A1:H1 → Click **Bold** in the Home tab.

2. **Center Align Headers**:  
   Select A1:H1 → Click **Center Align**.

3. **Number Format**:  
   Select B2:E4 → Apply **Number Format** or **Currency** (Home tab > Number section).

4. **Conditional Formatting for Status**:  
   - Select H2:H4  
   - Go to **Home > Conditional Formatting > New Rule**  
     - Rule 1: Cell Value = "Pass" → Green fill  
     - Rule 2: Cell Value = "Fail" → Red fill  

5. **Add Borders**:  
   Select A1:H4 → Click **Borders** in the Font section to outline the table.

---

## ✅ Final Output

| Student Name | Subject 1 | Subject 2 | Subject 3 | Subject 4 | Total | Average | Status |
|--------------|-----------|-----------|-----------|-----------|-------|---------|--------|
| John Doe     | 80        | 70        | 90        | 85        | 325   | 81.25   | Pass   |
| Jane Smith   | 85        | 95        | 78        | 88        | 346   | 86.5    | Pass   |
| Mike Johnson | 60        | 58        | 74        | 82        | 274   | 68.5    | Pass   |

---

## 💾 Step 5: Save Your Work

After completing all calculations and formatting steps, **save your workbook** to preserve your work.
