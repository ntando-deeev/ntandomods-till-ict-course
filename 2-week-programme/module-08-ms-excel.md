# Module 8 — Microsoft Excel: Spreadsheets & Basic Formulas
**Programme:** 2-Week Short Course | **Day:** 8 | **Duration:** 4 Hours  
**Powered by NtandoMods**

---

## 🎯 Learning Outcomes
By the end of this module, learners will be able to:
- Create and navigate a spreadsheet
- Enter data into cells correctly
- Use basic formulas: SUM, AVERAGE, MIN, MAX
- Format a spreadsheet for business use
- Create a simple till report in Excel

---

## 📖 Lesson 8.1 — Introduction to Excel (45 minutes)

### What is Excel Used For in Retail?
- Daily sales reports
- Stock lists and inventory counts
- Staff rosters and wages
- Cash-up records
- Expense tracking

### The Excel Interface
```
┌────┬──────┬──────┬──────┬──────┐
│    │  A   │  B   │  C   │  D   │  ← COLUMNS
├────┼──────┼──────┼──────┼──────┤
│ 1  │      │      │      │      │  ← ROWS
│ 2  │      │      │      │      │
│ 3  │      │      │      │      │
└────┴──────┴──────┴──────┴──────┘
```
- **Columns** are labelled A, B, C, D...
- **Rows** are numbered 1, 2, 3...
- Each box is called a **CELL** — named by column + row (e.g. **A1**, **B3**, **C12**)
- The **Formula Bar** at the top shows the content of the selected cell

---

## 📖 Lesson 8.2 — Entering & Editing Data (45 minutes)

### Entering Data
1. Click on a cell
2. Type your data
3. Press **Enter** to confirm and move down
4. Press **Tab** to confirm and move right

### Types of Data
| Type | Example | Excel Treatment |
|------|---------|----------------|
| Text | "Bread" | Left-aligned |
| Number | 2.50 | Right-aligned |
| Date | 04/06/2026 | Right-aligned |
| Formula | =A1+B1 | Shows result |

### Editing a Cell
- Double-click the cell to edit inside it
- Or click the cell and edit in the Formula Bar

### Deleting Data
- Click the cell and press **Delete** key

---

## 📖 Lesson 8.3 — Basic Formulas (60 minutes)

> All formulas in Excel start with the **=** sign

### SUM — Add up a range of numbers
```
=SUM(B2:B10)
```
Adds all values from B2 down to B10

### AVERAGE — Calculate the average
```
=AVERAGE(B2:B10)
```

### MIN — Find the lowest value
```
=MIN(B2:B10)
```

### MAX — Find the highest value
```
=MAX(B2:B10)
```

### Simple addition/subtraction
```
=A1+B1     (adds two cells)
=A1-B1     (subtracts)
=A1*B1     (multiplies)
=A1/B1     (divides)
```

### Practical Formula Example — Daily Sales Report
| | A | B | C | D |
|--|--|--|--|--|
| 1 | Item | Units Sold | Unit Price | Total |
| 2 | Bread | 50 | 0.90 | =B2*C2 |
| 3 | Milk | 30 | 1.50 | =B3*C3 |
| 4 | Sugar | 20 | 2.00 | =B4*C4 |
| 5 | **TOTAL** | | | =SUM(D2:D4) |

---

## 📖 Lesson 8.4 — Formatting a Spreadsheet (45 minutes)

### Making a Spreadsheet Look Professional
1. **Bold the headers** — click Row 1, press Ctrl + B
2. **Adjust column width** — double-click the column border to auto-fit
3. **Add borders** — select cells → Home → Borders → All Borders
4. **Format as currency** — select number cells → Home → "$" icon
5. **Fill colour** — select headers → Home → Fill Color → choose colour

### Freezing the Top Row (useful for long spreadsheets)
1. Click on Row 2 (the row below your headers)
2. Click View → Freeze Panes → Freeze Top Row
3. Now when you scroll down, headers stay visible

---

## 🔄 Practical Assignment

**Build a Weekly Till Report in Excel:**

Create a spreadsheet with:
- Column A: Day (Monday to Saturday)
- Column B: Cash Sales ($)
- Column C: EcoCash Sales ($)
- Column D: Card Sales ($)
- Column E: Total Sales (formula: =B+C+D)
- Row 9: TOTALS using SUM formula
- Row 10: AVERAGE using AVERAGE formula
- Row 11: BEST DAY using MAX formula

Enter realistic made-up figures and format professionally with borders, bold headers, and currency formatting.

---

## 📝 End of Day Quiz

1. What does a cell name like "C5" mean?
2. Write the formula to add all values in cells B1 to B7.
3. What is the difference between SUM and AVERAGE?
4. What does every Excel formula start with?
5. How do you freeze the top row of a spreadsheet?

---

*Module 8 Complete | NtandoMods 2026*
