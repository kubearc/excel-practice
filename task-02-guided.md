"""# 📊 Excel Task: Using Home Tab and Basic Formulas

This guide will help you create an Excel spreadsheet to manage item purchases using basic formulas and Home tab features such as formatting and conditional logic.

---

## 🛠️ 1. Set Up the Basic Structure

In **row 1**, use these headers:

| Cell | Header             |
|------|--------------------|
| A1   | Item               |
| B1   | Quantity           |
| C1   | Price per Item     |
| D1   | Total Cost         |
| E1   | Discount Applied   |
| F1   | Discounted Total   |

---

## 🧾 2. Enter Sample Data

In rows **2 and below**, add item data:

| Item     | Quantity | Price per Item |
|----------|----------|----------------|
| Item 1   | 10       | $20            |
| Item 2   | 5        | $15            |
| Item 3   | 20       | $10            |

---

## ➗ 3. Apply Formula for Total Cost

In **D2**, enter:

```excel
=B2*C2
Then copy it down for other rows.

🔄 4. Add Conditional Logic for Discount
In E2, enter:

excel
Always show details

Copy
=IF(D2>100, "Yes", "No")
This will apply a discount conditionally based on the total cost.

💰 5. Calculate Discounted Total
In F2, enter:

excel
Always show details

Copy
=IF(E2="Yes", D2*0.9, D2)
This gives a 10% discount if applicable.

🎨 6. Apply Conditional Formatting
✅ Highlight Total Cost > $100
Select column D from D2 down.

Home tab > Conditional Formatting > New Rule.

Format only cells that contain: Value > 100.

Choose a fill color (e.g., green).

🟡 Highlight Discounted Items
Select column F from F2 down.

Home tab > Conditional Formatting > New Rule.

Format cells with values less than original total (column D).

Choose a fill color (e.g., yellow).

🧾 7. Final Sheet Preview
Item	Quantity	Price per Item	Total Cost	Discount Applied	Discounted Total
Item 1	10	         $20	          $200         	Yes            	$180
Item 2	5          	$15           	$75         	No	            $75
Item 3	20	        $10           	$200	        Yes            	$180

💾 8. Save Your Work
Be sure to save your workbook when finished!
