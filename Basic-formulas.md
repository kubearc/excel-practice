#  **Advanced Excel Task (Hard Level)**

##  **Data Setup**

Enter the following data exactly as shown:

| A (Sales) | B (Names) | C (Remarks) |
| --------- | --------- | ----------- |
| 120       | Rahul     | Completed   |
| 85        | Priya     |             |
|           | Aman      | Pending     |
| 240       | Neha      | Completed   |
| -15       |           | Cancelled   |
| 310       | Rohan     | Completed   |
| 0         | Kavita    |             |
|           | Simran    | Pending     |

---

## ✅ **Tasks to Perform**

###  1. MAX & MIN (Advanced Condition Thinking)

* Find the **maximum sales value** (ignore blanks)
* Find the **minimum sales value** (including negative values)


---

###  2. LENGTH (LEN Function with Spaces Trick)

Find length of:

* `"   Rahul"`
* `"Simran   "`

👉 Note: Spaces are counted!



---

### 🔢 3. COUNT Functions (Tricky Case)

Apply on **column A (Sales)**:

* COUNT
* COUNTA
* COUNTBLANK 

---

###  4. TRIM (Real-Life Messy Data)

Apply TRIM to clean:

* `"   Rahul   "`
* `"   Rohan"`

---

###  5. CONCATENATE (With Logic)

Create a full sentence:

👉 Combine:

* Name (Column B)
* Remarks (Column C)

Example Output:

* Rahul has status Completed

⚠️ Handle blank cells carefully!

---

###  6. CURRENT DATE & TIME (Formatting Challenge)

* Show current **date only**
* Show current **date & time**
* Format:

  * Date → `DD-MMM-YYYY`
  * Date & Time → `DD/MM/YYYY HH:MM`

---

---

## 🔥 **Bonus Challenge (Very Hard)**

👉 Create a formula that:

* Ignores blank names
* Removes extra spaces
* Then concatenates clean name + status
