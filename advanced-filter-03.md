## **Excel Expert Task: Dynamic Advanced Filter with Duplicate Detection & Conditional Extraction**

###  **Objective**

Use **Advanced Filter** in Microsoft Excel to:

* Extract **duplicate records**
* Apply **multiple conditional logic**
* Use **formula-based dynamic filtering**

---

## Create Dataset

| Order ID | Customer | City    | Product | Amount | Status    |
| -------- | -------- | ------- | ------- | ------ | --------- |
| 101      | Aman     | Delhi   | Laptop  | 55000  | Delivered |
| 102      | Neha     | Mumbai  | Mobile  | 20000  | Pending   |
| 103      | Raj      | Delhi   | Tablet  | 30000  | Delivered |
| 104      | Simran   | Chennai | Laptop  | 65000  | Cancelled |
| 105      | Aman     | Delhi   | Laptop  | 55000  | Delivered |
| 106      | Karan    | Mumbai  | Mobile  | 22000  | Delivered |
| 107      | Ravi     | Delhi   | Laptop  | 70000  | Pending   |
| 108      | Neha     | Mumbai  | Mobile  | 20000  | Pending   |

### **Task A: Extract Duplicate Orders**

 Find records where:

* Same **Customer + Product + Amount** appears more than once

### **Expected Output**

 Duplicate entries (Aman Laptop 55000, Neha Mobile 20000)

###  **Task B: High-Value Delivered Orders (Complex AND Condition)**

###  Condition:

* Status = Delivered
* Amount > 50000
* City = Delhi

###  **Task C: Mixed OR + Formula Logic**

### Condition:

* Orders from **Mumbai** with Amount > 20000
  **OR**
* Orders where Product = Laptop AND Status ≠ Cancelled

###  **Task D:  (Dynamic Condition)**

 Extract records where:

* Amount is **greater than average of all orders**
* Status is **not Pending**
