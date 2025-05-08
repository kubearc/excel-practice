
# Basic Excel Formulas & Functions with Examples

This guide covers essential Excel formulas and functions along with practical examples for quick understanding and reference.

---

## 📌 SUM
Adds up values.

**Syntax:**
```excel
SUM(number1, [number2], …)
````

**Examples:**

```excel
=SUM(B2:B6)       // Adds values from B2 to B6
=SUM(B2, B6)      // Adds values in B2 and B6
=SUM(B2:B6)/5     // Averages values from B2 to B6 manually
=SUMIF(A2:A6, D2, B2:B6)  // Conditional sum
```

**Tip:** Use the AutoSum button for a quick total.

---

## 📌 AVERAGE

Finds the arithmetic mean of a range of numbers.

**Syntax:**

```excel
AVERAGE(number1, [number2], …)
```

**Examples:**

```excel
=AVERAGE(B2:B6)  // Average of B2 to B6
=AVERAGEIF(A2:A6, D3, B2:B6)  // Conditional average
```

---

## 📌 MAX & MIN

Find the largest and smallest values.

**Examples:**

```excel
=MAX(B2:B6)
=MIN(B2:B6)
```

---

## 📌 COUNT & COUNTA

Count numeric or non-empty cells.

**Syntax:**

```excel
COUNT(value1, [value2], …)
COUNTA(value1, [value2], …)
```

**Examples:**

```excel
=COUNT(B:B)    // Count numbers
=COUNTA(B:B)   // Count non-empty cells
```

---

## 📌 IF

Returns values based on a condition.

**Syntax:**

```excel
IF(logical_test, [value_if_true], [value_if_false])
```

**Example:**

```excel
=IF(C2<>"", "Yes", "No")  // Check if cell is not empty
```

---

## 📌 TRIM

Removes extra spaces from text.

**Syntax:**

```excel
TRIM(text)
```

**Example:**

```excel
=TRIM(A1)
```

---

## 📌 LEN

Counts the number of characters, including spaces.

**Syntax:**

```excel
LEN(text)
```

**Example:**

```excel
=LEN(A2)
```

---

## 📌 AND & OR

Evaluate multiple conditions.

* `AND`: Returns TRUE if **all** conditions are met.
* `OR`: Returns TRUE if **any** condition is met.

**Examples:**

```excel
=IF(AND(B2>60, C2>60), "Pass", "Fail")
=IF(OR(B2>60, C2>60), "Pass", "Fail")
```

---

## 📌 CONCATENATE

Joins multiple text strings into one.

**Syntax:**

```excel
CONCATENATE(text1, [text2], …)
```

**Examples:**

```excel
=CONCATENATE(A2, B2)
=CONCATENATE(A2, " ", B2)
```

---

## 📌 TODAY & NOW

Insert current date or date and time.

**Examples:**

```excel
=TODAY()   // Current date
=NOW()     // Current date and time
```

---

> This cheat sheet is designed for learners and professionals to reference basic Excel functionality easily and efficiently.

```


