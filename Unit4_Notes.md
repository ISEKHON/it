# UNIT 4: Spreadsheet Software

## 1. Spreadsheet Overview

### What is a Spreadsheet?
A **spreadsheet** is a software application that organizes, analyzes, and stores data in **tabular form** (rows and columns). It's like a digital ledger or table with powerful calculation and data analysis capabilities.

**Popular Spreadsheet Software:**
- **Microsoft Excel** (most popular, industry standard)
- **Google Sheets** (online, free, collaborative)
- **LibreOffice Calc** (free, open-source)
- **Apache OpenOffice Calc** (free)
- **Apple Numbers** (Mac)

---

### Basic Components of a Spreadsheet

#### 1. Workbook
- **Definition**: The entire spreadsheet file (e.g., "Budget.xlsx")
- Contains one or more worksheets
- File extensions: .xlsx (Excel), .ods (Calc), .gsheet (Google Sheets)

#### 2. Worksheet (Sheet)
- **Definition**: Individual page/tab within a workbook
- Contains grid of cells
- Default: Sheet1, Sheet2, Sheet3...
- Can be renamed (e.g., "January", "Sales", "Inventory")
- **Tabs** at bottom to switch between sheets

#### 3. Cell
- **Definition**: Intersection of row and column (basic unit of spreadsheet)
- **Cell Reference/Address**: Column letter + Row number
  - Examples: A1, B5, Z100, AA1
- **Active Cell**: Currently selected cell (highlighted border)
- Can contain: Text, numbers, formulas, dates

#### 4. Rows
- **Horizontal** lines of cells
- Numbered: 1, 2, 3, 4... up to 1,048,576 (Excel)
- **Row header**: Number on left side
- Select entire row: Click row number

#### 5. Columns
- **Vertical** lines of cells
- Lettered: A, B, C... Z, AA, AB... up to XFD (Excel = 16,384 columns)
- **Column header**: Letter at top
- Select entire column: Click column letter

#### 6. Cell Range
- **Definition**: Group of cells (rectangular block)
- **Notation**: TopLeft:BottomRight
  - **A1:D4** = cells from A1 to D4 (4×4 grid)
  - **A:A** = entire column A
  - **1:1** = entire row 1
  - **A1:Z100** = large range
- Used in formulas and formatting

#### 7. Formula Bar
- Shows contents of active cell
- Edit cell contents here
- Displays formulas (cells show results)

#### 8. Name Box
- Left of formula bar
- Shows active cell address (e.g., B5)
- Can type cell address to jump to it
- Create named ranges (give cell/range a name)

---

### Understanding Cell References

#### A. Absolute vs Relative References

##### Relative Reference (default)
- **Notation**: A1, B2, C3
- **Behavior**: Changes when copied/moved
- **Example**:
  ```
  Cell C1: =A1+B1
  Copy to C2: =A2+B2 (adjusts automatically)
  Copy to C3: =A3+B3
  ```
- **Use**: When formula should adapt to new position

##### Absolute Reference
- **Notation**: $A$1 ($ locks the reference)
- **Behavior**: Does NOT change when copied
- **Example**:
  ```
  Cell C1: =A1*$B$1 (multiply by value in B1)
  Copy to C2: =A2*$B$1 (still refers to B1)
  Copy to C3: =A3*$B$1 (still refers to B1)
  ```
- **Use**: When reference should always point to same cell (tax rate, conversion factor)
- **Shortcut**: Press F4 to toggle $ signs

##### Mixed Reference
- **Notation**: $A1 (column locked) or A$1 (row locked)
- **Examples**:
  - **$A1**: Column A fixed, row changes
  - **A$1**: Row 1 fixed, column changes
- **Use**: Multiplication tables, complex formulas

**Summary Table:**

| Reference | Example | Copy Right | Copy Down | Use Case |
|-----------|---------|------------|-----------|----------|
| Relative | A1 | B1 | A2 | Default (adapts) |
| Absolute | $A$1 | $A$1 | $A$1 | Fixed value (constant) |
| Mixed (col) | $A1 | $A1 | $A2 | Column fixed |
| Mixed (row) | A$1 | B$1 | A$1 | Row fixed |

---

### Uses of Spreadsheets

#### 1. Financial Applications
- **Budgeting**: Personal/business budgets
- **Accounting**: Ledgers, balance sheets
- **Expense tracking**: Monthly expenses
- **Loan calculations**: EMI, interest
- **Investment analysis**: Portfolio tracking
- **Payroll**: Salary calculations, tax deductions
- **Profit/Loss statements**: Business financials

#### 2. Data Analysis
- **Statistical analysis**: Mean, median, standard deviation
- **Trend analysis**: Sales trends over time
- **Forecasting**: Predict future values
- **What-if analysis**: Change variables, see impact
- **Data sorting**: Organize data alphabetically, numerically
- **Filtering**: Show only specific records
- **Pivot tables**: Summarize large datasets

#### 3. Scientific and Academic
- **Lab data**: Record experimental results
- **Grade books**: Student marks, averages
- **Research data**: Organize research findings
- **Survey results**: Tabulate responses
- **Statistical calculations**: Hypothesis testing
- **Graphs**: Visualize scientific data

#### 4. Business Management
- **Inventory management**: Stock levels, reorder points
- **Sales tracking**: Daily/monthly sales
- **Customer databases**: Contact lists
- **Project planning**: Timelines, resource allocation
- **Performance metrics**: KPIs, dashboards
- **Scheduling**: Work rosters, event calendars

#### 5. Personal Use
- **Shopping lists**: Organized lists with prices
- **Fitness tracking**: Weight, calories, exercise logs
- **Travel planning**: Itineraries, expense tracking
- **Wedding planning**: Guest lists, budgets
- **Recipe books**: Ingredients, quantities
- **Home inventory**: Belongings for insurance

---

### Advantages of Spreadsheets

✅ **Automatic calculations**: Formulas compute instantly  
✅ **Error reduction**: Less manual calculation errors  
✅ **What-if analysis**: Change values, see impact immediately  
✅ **Data organization**: Neat, structured format  
✅ **Visual representation**: Charts and graphs  
✅ **Easy modification**: Update formulas, recalculates automatically  
✅ **Reusability**: Save templates, reuse structure  
✅ **Large datasets**: Handle millions of rows  
✅ **Sorting & filtering**: Find data quickly  
✅ **Collaboration**: Share and co-edit (Google Sheets)  

---

## 2. Editing in Spreadsheets

### Entering Data

#### Entering Text
- Click cell
- Type text (letters, words)
- Press **Enter** (move down) or **Tab** (move right)
- **Text alignment**: Left-aligned by default
- **Long text**: Overflows into next cell if empty, or gets cut off
- **Wrap text**: Home → Wrap Text (shows full text in multiple lines within cell)

#### Entering Numbers
- Type numbers (0-9, decimal point, minus sign)
- Press Enter/Tab
- **Number alignment**: Right-aligned by default
- **Leading zeros**: Type apostrophe first ('007 becomes 007, not 7)
- **Negative numbers**: Use minus sign (-100)
- **Percentages**: Type number followed by % (50% or 0.5)
- **Fractions**: Type 0 1/2 (for ½, otherwise 1/2 becomes date)

#### Entering Dates and Times
- **Dates**: 
  - Type: 12/7/2025 or Dec 7, 2025 or 7-Dec-25
  - Automatically recognized as date
  - Stored as serial number (days since Jan 1, 1900)
  - Can be formatted (Short Date, Long Date)
- **Times**: 
  - Type: 2:30 PM or 14:30
  - Stored as decimal (0.5 = 12:00 PM)
- **Date + Time**: 12/7/2025 2:30 PM
- **Current date**: Ctrl + ; (semicolon)
- **Current time**: Ctrl + Shift + : (colon)

#### Entering Formulas
- **Always start with = sign**
- Type formula (e.g., =A1+B1)
- Press Enter
- Cell shows **result**, formula bar shows **formula**
- **Click cells** instead of typing addresses (easier, fewer errors)

---

### Selecting Cells and Ranges

#### Selecting Single Cell
- Click cell
- Border appears (active cell)

#### Selecting Range
- **Method 1**: Click and drag
- **Method 2**: Click first cell, hold Shift, click last cell
- **Method 3**: Type range in Name Box (e.g., A1:D10), press Enter

#### Selecting Row/Column
- **Row**: Click row number (selects entire row)
- **Column**: Click column letter (selects entire column)
- **Multiple rows**: Click first row number, hold Shift, click last row
- **Multiple columns**: Same with columns

#### Selecting Entire Sheet
- **Ctrl + A** (all cells)
- Or click intersection of row/column headers (top-left corner)

#### Non-Adjacent Ranges
- Select first range
- Hold **Ctrl**
- Select other ranges
- Example: A1:A10, C1:C10, E1:E10 (selected together)

---

### Editing Cell Contents

#### Edit in Cell
- **Double-click cell**: Edit directly in cell
- Type changes
- Press Enter

#### Edit in Formula Bar
- Click cell
- Click in formula bar
- Edit text/formula
- Press Enter

#### Clear Cell Contents
- Select cell(s)
- Press **Delete** (clears content, keeps formatting)
- Or right-click → Clear Contents

#### Clear Formatting
- Select cell(s)
- Home → Clear → Clear Formats
- Keeps content, removes formatting

#### Clear All
- Select cell(s)
- Home → Clear → Clear All
- Removes content AND formatting

---

### Cut, Copy, and Paste

#### Copy
- Select cell(s)
- **Ctrl + C** (copy)
- Select destination
- **Ctrl + V** (paste)
- Original remains unchanged

#### Cut
- Select cell(s)
- **Ctrl + X** (cut)
- Select destination
- **Ctrl + V** (paste)
- Original is moved (removed from original location)

#### Paste Special
- Copy data
- Right-click destination → Paste Special
- **Options**:
  - **Values**: Paste only values (not formulas)
  - **Formulas**: Paste formulas (not formatting)
  - **Formats**: Paste only formatting (not content)
  - **Transpose**: Swap rows and columns
  - **Operations**: Add, subtract, multiply, divide with existing data
- **Shortcut**: Ctrl + Alt + V

**Example - Transpose:**
```
Original:        After Transpose:
A  B  C          A  1
1  2  3          B  2
                 C  3
```

---

### Inserting and Deleting

#### Insert Rows
- Right-click row number → Insert
- New row appears **above** selected row
- **Shortcut**: Ctrl + Shift + + (plus)
- **Multiple rows**: Select multiple rows, then insert

#### Insert Columns
- Right-click column letter → Insert
- New column appears to **left** of selected column
- **Shortcut**: Ctrl + Shift + +
- **Multiple columns**: Select multiple columns, then insert

#### Insert Cells
- Right-click cell → Insert
- Choose:
  - Shift cells right
  - Shift cells down
  - Entire row
  - Entire column

#### Delete Rows/Columns
- Right-click row/column → Delete
- **Shortcut**: Ctrl + - (minus)
- Removes entire row/column

#### Delete Cells
- Right-click cell → Delete
- Choose:
  - Shift cells left
  - Shift cells up
  - Entire row
  - Entire column

---

### Undo and Redo

#### Undo
- **Ctrl + Z**: Undo last action
- Repeat to undo multiple actions
- **Undo dropdown**: Click dropdown arrow (shows history)

#### Redo
- **Ctrl + Y**: Redo (restore undone action)
- Only works after undo

---

### Find and Replace

#### Find
- **Ctrl + F**: Open Find dialog
- Type search term
- **Options**:
  - Match case (uppercase/lowercase matters)
  - Match entire cell contents
  - Search within: Sheet or Workbook
- **Find Next**: Next occurrence
- **Find All**: List all matches

#### Replace
- **Ctrl + H**: Open Find and Replace dialog
- **Find what**: Text to search
- **Replace with**: New text
- **Options**:
  - Replace: Single replacement
  - Replace All: All occurrences
  - Match case
  - Match entire cell contents
- **Uses**: 
  - Fix repeated typos
  - Update product names
  - Change formulas in bulk

---

### AutoFill and Fill Handle

#### Fill Handle
- **Small square** at bottom-right corner of active cell
- Drag to copy content or create series

#### AutoFill Types

##### 1. Copy Same Value
- Enter value in cell
- Drag fill handle
- Same value copied to all cells

##### 2. Number Series
- Enter 1, 2 (two consecutive numbers)
- Select both
- Drag fill handle
- Creates series: 3, 4, 5, 6...

##### 3. Date Series
- Enter date (e.g., Jan 1)
- Drag fill handle
- Creates series: Jan 2, Jan 3, Jan 4...
- Right-click drag for options (fill weekdays, months, years)

##### 4. Custom Lists
- Days: Monday → drag → Tuesday, Wednesday...
- Months: January → drag → February, March...
- Quarter: Q1 → drag → Q2, Q3, Q4

##### 5. Formula Fill
- Enter formula in first cell (e.g., =A1*2)
- Drag fill handle down
- Formula adjusts: =A2*2, =A3*2... (relative reference)

**Fill Options:**
- After dragging, **AutoFill Options** button appears
- Choose:
  - Copy Cells
  - Fill Series
  - Fill Formatting Only
  - Fill Without Formatting

---

## 3. Formatting in Spreadsheets

### Number Formatting

#### General (Default)
- No specific format
- Numbers as entered

#### Number
- Home → Number Format → Number
- **Decimal places**: 2 (default) - e.g., 1234.56
- **Thousand separator**: Comma (1,234.56)
- **Negative numbers**: Red with minus or parentheses

#### Currency
- **Symbol**: $ (or ₹, €, £ based on region)
- **Format**: $1,234.56 or ₹1,234.56
- **Shortcut**: Ctrl + Shift + $
- Automatically includes:
  - Thousand separator
  - 2 decimal places
  - Currency symbol

#### Accounting
- Similar to currency
- **Difference**: Aligns currency symbols vertically
- Better for financial statements
- Negative numbers in parentheses

#### Percentage
- Multiplies value by 100 and adds %
- **Example**: 0.5 becomes 50%
- **Shortcut**: Ctrl + Shift + %
- **Decimal places**: Adjustable

#### Date
- **Short Date**: 12/7/2025
- **Long Date**: Wednesday, December 7, 2025
- **Custom**: dd-mmm-yyyy (07-Dec-2025)
- Right-click → Format Cells → Date → Choose format

#### Time
- **12-hour**: 2:30 PM
- **24-hour**: 14:30
- **With seconds**: 2:30:45 PM

#### Fraction
- Displays as fraction (e.g., 0.5 becomes 1/2)
- Types: Halves, quarters, eighths, sixteenths, tenths, hundredths

#### Scientific
- **Exponential notation**: 1.23E+03 (= 1230)
- Used for very large or very small numbers

#### Text
- Treats number as text (left-aligned)
- Use for: Phone numbers, ZIP codes, product codes
- Prevents calculations

#### Custom
- Create your own format
- **Format Codes**:
  - **0**: Digit placeholder (shows 0 if empty)
  - **#**: Digit placeholder (doesn't show if empty)
  - **m**: Month (1-12)
  - **d**: Day (1-31)
  - **y**: Year (2-digit or 4-digit)
- **Examples**:
  - **#,##0.00**: Thousand separator, 2 decimals
  - **dd/mm/yyyy**: Date format
  - **[Red]-#,##0.00**: Negative numbers in red

**Access Number Formatting:**
- Home → Number Format dropdown
- Or Ctrl + 1 → Number tab

---

### Font Formatting

#### Font Face
- Home → Font dropdown
- Common: Arial, Calibri, Times New Roman, Verdana
- Choose readable font (avoid decorative for data)

#### Font Size
- Home → Font Size dropdown
- Default: 11 pt
- Range: 8-72 pt (can type custom)
- **Shortcuts**:
  - Ctrl + Shift + > (increase)
  - Ctrl + Shift + < (decrease)

#### Font Style
- **Bold**: Ctrl + B (emphasize headers, totals)
- **Italic**: Ctrl + I (notes, comments)
- **Underline**: Ctrl + U (headings)
- **Strikethrough**: Completed tasks, discontinued items

#### Font Color
- Home → Font Color
- Choose from palette or custom RGB
- Use for:
  - Headers (dark blue)
  - Warnings (red)
  - Positive values (green), negative (red)

#### Fill Color (Cell Background)
- Home → Fill Color
- Highlights cells
- Use for:
  - Headers (light blue/gray)
  - Totals (yellow)
  - Alternate rows (light gray for readability)
  - Conditional categories

---

### Alignment

#### Horizontal Alignment
- **Left**: Text default, Ctrl + L
- **Center**: Headings, Ctrl + E
- **Right**: Numbers default, Ctrl + R
- **Justify**: Fit text edge-to-edge

#### Vertical Alignment
- **Top**: Content at top of cell
- **Middle**: Centered vertically (default)
- **Bottom**: Content at bottom

#### Indent
- Move text away from cell edge
- Home → Increase Indent / Decrease Indent
- Creates hierarchy (like outlining)

#### Orientation
- Rotate text
- Options: Angle upward, angle downward, vertical text, rotate 90°
- Use for: Narrow columns with long headers

#### Wrap Text
- Home → Wrap Text
- Displays long text in multiple lines within cell
- Cell height increases automatically
- Use when: Text longer than column width

#### Merge Cells
- Combine multiple cells into one
- Home → Merge & Center
- **Options**:
  - **Merge & Center**: Combine and center text
  - **Merge Across**: Merge each row separately
  - **Merge Cells**: Combine without centering
  - **Unmerge Cells**: Split back to individual cells
- **Use**: Create centered titles spanning multiple columns
- **Warning**: Only keeps upper-left cell value (deletes others)

---

### Borders and Gridlines

#### Borders
- Home → Borders dropdown
- **Types**:
  - Bottom Border (underline)
  - Top Border
  - Left/Right Border
  - All Borders (box around cells)
  - Outside Borders (outline of range)
  - Thick Box Border
  - Double Bottom Border (for totals)
  - No Border (remove)
- **Customize**: 
  - Line style (solid, dashed, dotted, double)
  - Line color
  - Line thickness
- **Use**:
  - Separate sections
  - Emphasize totals (double underline)
  - Create tables

#### Draw Borders
- Home → Borders → Draw Border
- Click and drag to draw custom borders
- Draw Border Grid (creates grid)

#### Gridlines
- Faint lines showing cell boundaries
- **View**: View tab → Gridlines checkbox
- **Print**: Page Layout → Print Gridlines (if you want them in printout)
- **Default**: Visible on screen, not printed

---

### Cell Styles

#### Predefined Styles
- Home → Cell Styles gallery
- **Categories**:
  - **Good, Bad, Neutral**: Green, red, yellow backgrounds
  - **Data and Model**: Calculation, check cell, explanatory text, input, linked cell, note, output, warning text
  - **Titles and Headings**: Heading 1-4, Title, Total
  - **Themed Cell Styles**: Accent colors (1-6), 20%/40%/60% tints
  - **Number Format**: Comma, currency, percent

#### Create Custom Style
- Format cells as desired
- Home → Cell Styles → New Cell Style
- Name it
- Save for reuse

#### Modify Style
- Home → Cell Styles → Right-click style → Modify
- Change formatting
- All cells using that style update automatically

---

### Conditional Formatting

#### What is Conditional Formatting?
**Automatically apply formatting** based on cell values. Visual representation of data patterns.

#### Types of Conditional Formatting

##### 1. Highlight Cells Rules
- **Greater Than**: Highlight cells > specific value (e.g., sales > $1000)
- **Less Than**: Highlight cells < value
- **Between**: Range (e.g., 50-100)
- **Equal To**: Exact match
- **Text That Contains**: Cells containing specific word
- **Duplicate Values**: Find duplicates/unique values
- **Date Occurring**: Today, yesterday, tomorrow, this week, etc.

**Example:**
- Select sales column
- Conditional Formatting → Highlight Cells Rules → Greater Than
- Enter 1000
- Choose formatting (green fill)
- All sales > 1000 highlighted green

##### 2. Top/Bottom Rules
- **Top 10 Items**: Highlight top 10 values
- **Top 10%**: Highlight top 10 percent
- **Bottom 10 Items**: Highlight bottom 10
- **Above Average**: Highlight above average values
- **Below Average**: Highlight below average

##### 3. Data Bars
- **Horizontal bars** inside cells
- Bar length = value magnitude
- Visual comparison
- Color options: Blue, green, red, orange, etc.
- **Use**: Budget spent, task completion %

##### 4. Color Scales
- **Gradient coloring** based on value
- **2-Color Scale**: Low (red) → High (green)
- **3-Color Scale**: Low (red) → Mid (yellow) → High (green)
- **Use**: Heat maps, performance ratings

##### 5. Icon Sets
- **Icons** based on value ranges
- **Types**:
  - Arrows (up, down, sideways) - trend
  - Traffic lights (red, yellow, green) - status
  - Stars (ratings)
  - Flags
  - Indicators
- **3, 4, or 5 levels**
- **Use**: KPIs, status tracking

##### 6. Custom Formula
- Write custom rule using formulas
- **Example**: Highlight entire row if status = "Complete"
  - Formula: `=$E1="Complete"` (apply to range A1:F100)
- **Advanced**: Complex conditions, multiple criteria

#### Manage Rules
- Conditional Formatting → Manage Rules
- View all rules
- Edit, delete, reorder rules
- Change priority (which rule applies first)

#### Clear Rules
- Conditional Formatting → Clear Rules
- From Selected Cells or Entire Sheet

**Uses:**
- **Performance dashboards**: Traffic light icons for KPIs
- **Sales targets**: Color scales (low to high sales)
- **Budget tracking**: Data bars for spending vs. budget
- **Deadline tracking**: Highlight overdue dates in red
- **Inventory alerts**: Highlight low stock in red

---

### Column Width and Row Height

#### Adjust Column Width
- **Method 1**: Drag column border (between column letters)
- **Method 2**: Right-click column → Column Width → Enter value
- **Auto-fit**: Double-click column border (fits widest content)
- **Set specific width**: Select columns → Home → Format → Column Width

#### Adjust Row Height
- **Method 1**: Drag row border (between row numbers)
- **Method 2**: Right-click row → Row Height → Enter value
- **Auto-fit**: Double-click row border (fits tallest content)

#### Hide Rows/Columns
- Right-click row/column → Hide
- **Hidden indicator**: Row numbers/column letters skip (A, B, D... C is hidden)
- **Unhide**: Select rows/columns on both sides → Right-click → Unhide

#### Default Size
- **Column width**: 8.43 characters (64 pixels)
- **Row height**: 15 points (20 pixels)

---

## 4. Creating Formulas

### What is a Formula?
An **equation** that performs calculations on values in the spreadsheet. Always begins with **=** sign.

### Operators

#### Arithmetic Operators
| Operator | Meaning | Example | Result |
|----------|---------|---------|--------|
| + | Addition | =5+3 | 8 |
| - | Subtraction | =10-4 | 6 |
| * | Multiplication | =6*7 | 42 |
| / | Division | =20/4 | 5 |
| ^ | Exponentiation | =2^3 | 8 (2³) |
| % | Percentage | =50% | 0.5 |

#### Comparison Operators
| Operator | Meaning | Example | Result |
|----------|---------|---------|--------|
| = | Equal to | =A1=B1 | TRUE/FALSE |
| > | Greater than | =A1>10 | TRUE/FALSE |
| < | Less than | =A1<5 | TRUE/FALSE |
| >= | Greater than or equal | =A1>=10 | TRUE/FALSE |
| <= | Less than or equal | =A1<=5 | TRUE/FALSE |
| <> | Not equal to | =A1<>B1 | TRUE/FALSE |

#### Text Operator
| Operator | Meaning | Example | Result |
|----------|---------|---------|--------|
| & | Concatenation (join text) | ="Hello"&" "&"World" | Hello World |

#### Order of Operations (PEMDAS/BODMAS)
1. **Parentheses** / **Brackets** ( )
2. **Exponentiation** ^
3. **Multiplication** * and **Division** / (left to right)
4. **Addition** + and **Subtraction** - (left to right)

**Examples:**
- =5+3*2 → 11 (not 16, because * before +)
- =(5+3)*2 → 16 (parentheses first)
- =10/2*5 → 25 (left to right: 10/2=5, then 5*5=25)

---

### Basic Formulas

#### Simple Calculations
```
=10+20           → 30
=A1+B1           → Sum of cells A1 and B1
=A1-B1           → Difference
=A1*B1           → Product
=A1/B1           → Quotient
=(A1+B1)/2       → Average of two cells
=A1^2            → A1 squared
```

#### Cell References in Formulas
```
=A1+A2+A3        → Sum of three cells
=B5*C5           → Multiply two cells
=(C5-D5)/D5*100  → Percentage change
```

---

### Functions

#### What is a Function?
**Predefined formula** that performs specific calculation. Syntax: `=FUNCTION_NAME(arguments)`

---

### Common Functions

#### 1. SUM - Add Numbers
**Syntax:** `=SUM(number1, number2, ...)`  
**Purpose:** Adds all numbers in range

**Examples:**
```
=SUM(A1:A10)        → Sum of cells A1 to A10
=SUM(A1,B1,C1)      → Sum of three individual cells
=SUM(A1:A5,C1:C5)   → Sum of two ranges
=SUM(100,200,300)   → 600
```

**Shortcut:** Alt + = (AutoSum, inserts SUM for selected cells)

---

#### 2. AVERAGE - Calculate Average
**Syntax:** `=AVERAGE(number1, number2, ...)`  
**Purpose:** Calculates mean (average) of numbers

**Examples:**
```
=AVERAGE(A1:A10)    → Average of A1 to A10
=AVERAGE(85,90,78)  → 84.33 (average of three scores)
```

**Related:**
- **AVERAGEIF:** Average with condition (e.g., average sales > 1000)
- **AVERAGEIFS:** Multiple conditions

---

#### 3. MAX - Find Maximum Value
**Syntax:** `=MAX(number1, number2, ...)`  
**Purpose:** Returns largest value in range

**Examples:**
```
=MAX(A1:A10)        → Highest value in A1 to A10
=MAX(50,100,75)     → 100
```

---

#### 4. MIN - Find Minimum Value
**Syntax:** `=MIN(number1, number2, ...)`  
**Purpose:** Returns smallest value in range

**Examples:**
```
=MIN(A1:A10)        → Lowest value in A1 to A10
=MIN(50,100,75)     → 50
```

---

#### 5. COUNT - Count Numbers
**Syntax:** `=COUNT(value1, value2, ...)`  
**Purpose:** Counts how many cells contain numbers

**Examples:**
```
=COUNT(A1:A10)      → Counts numeric entries in A1 to A10
```

**Related:**
- **COUNTA:** Counts non-empty cells (numbers, text, dates)
- **COUNTBLANK:** Counts empty cells
- **COUNTIF:** Counts cells meeting criteria (e.g., count sales > 1000)
- **COUNTIFS:** Multiple criteria

**Examples:**
```
=COUNTA(A1:A10)            → Count non-empty cells
=COUNTBLANK(A1:A10)        → Count empty cells
=COUNTIF(A1:A10,">100")    → Count values > 100
=COUNTIF(A1:A10,"Apple")   → Count cells containing "Apple"
```

---

#### 6. IF - Conditional Logic
**Syntax:** `=IF(logical_test, value_if_true, value_if_false)`  
**Purpose:** Returns different values based on condition

**Examples:**
```
=IF(A1>10,"High","Low")              → If A1 > 10, show "High", else "Low"
=IF(B1>=50,"Pass","Fail")            → Pass/Fail based on marks
=IF(C1="","Empty","Not Empty")       → Check if cell is empty
=IF(A1>0,A1*0.1,0)                   → 10% if positive, else 0
```

**Nested IF:**
```
=IF(A1>=90,"A",IF(A1>=80,"B",IF(A1>=70,"C","Fail")))
   → Grade: A (90+), B (80-89), C (70-79), Fail (<70)
```

**Related:**
- **IFS:** Multiple conditions (easier than nested IF)
  ```
  =IFS(A1>=90,"A", A1>=80,"B", A1>=70,"C", TRUE,"Fail")
  ```

---

#### 7. SUMIF - Conditional Sum
**Syntax:** `=SUMIF(range, criteria, [sum_range])`  
**Purpose:** Sum values meeting specific criteria

**Examples:**
```
=SUMIF(A1:A10,">100")           → Sum values > 100 in A1:A10
=SUMIF(A1:A10,"Apple",B1:B10)   → Sum B values where A = "Apple"
=SUMIF(A1:A10,"<>0",B1:B10)     → Sum B values where A is not zero
```

**SUMIFS** (Multiple Criteria):
```
=SUMIFS(C1:C10, A1:A10, "Apple", B1:B10, ">100")
   → Sum C where A="Apple" AND B>100
```

---

#### 8. VLOOKUP - Vertical Lookup
**Syntax:** `=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])`  
**Purpose:** Search for value in first column, return value from another column

**Parameters:**
- **lookup_value:** What to search for
- **table_array:** Where to search (table range)
- **col_index_num:** Which column to return (1 = first column)
- **range_lookup:** TRUE (approximate match) or FALSE (exact match)

**Example:**
```
Product table (A1:C5):
  A          B        C
  Product    Price    Stock
  Apple      $1.50    100
  Banana     $0.80    200
  Orange     $2.00    150

=VLOOKUP("Banana", A2:C5, 2, FALSE)  → $0.80 (price of Banana)
=VLOOKUP("Orange", A2:C5, 3, FALSE)  → 150 (stock of Orange)
=VLOOKUP(E1, A2:C5, 2, FALSE)        → Price of product in E1
```

**Common Use:** Price lists, employee databases, product catalogs

**Related:**
- **HLOOKUP:** Horizontal lookup (search in rows)
- **XLOOKUP:** Modern, more flexible (Excel 365)

---

#### 9. Concatenation - Join Text
**Syntax:** `=CONCATENATE(text1, text2, ...)` or `text1 & text2 & ...`  
**Purpose:** Combine text from multiple cells

**Examples:**
```
=CONCATENATE(A1," ",B1)        → Join first name and last name
=A1&" "&B1                     → Same (using & operator)
="Hello "&A1                   → "Hello" + value in A1
=A1&", "&B1&", "&C1            → CSV format
```

**Modern:** `=TEXTJOIN(delimiter, ignore_empty, text1, text2, ...)`
```
=TEXTJOIN(", ", TRUE, A1:A10)  → Join A1 to A10 with comma separator
```

---

#### 10. Date and Time Functions

##### TODAY
**Syntax:** `=TODAY()`  
**Purpose:** Current date (updates daily)

**Example:**
```
=TODAY()                 → 12/7/2025 (today's date)
=TODAY()+7               → Date 7 days from now
=TODAY()-30              → Date 30 days ago
```

##### NOW
**Syntax:** `=NOW()`  
**Purpose:** Current date and time (updates continuously)

**Example:**
```
=NOW()                   → 12/7/2025 2:30 PM (current date/time)
```

##### YEAR, MONTH, DAY
**Extract parts of date:**
```
=YEAR(A1)                → Year from date in A1 (e.g., 2025)
=MONTH(A1)               → Month (1-12)
=DAY(A1)                 → Day (1-31)
```

##### DATE
**Syntax:** `=DATE(year, month, day)`  
**Purpose:** Create date from year, month, day

**Example:**
```
=DATE(2025,12,25)        → December 25, 2025
=DATE(A1,B1,C1)          → Date from cells A1=year, B1=month, C1=day
```

##### DATEDIF (Calculate Age/Duration)
**Syntax:** `=DATEDIF(start_date, end_date, unit)`  
**Purpose:** Difference between dates

**Units:**
- "Y" = Years
- "M" = Months
- "D" = Days
- "YM" = Months ignoring years
- "MD" = Days ignoring months and years

**Examples:**
```
=DATEDIF("1/1/2000", TODAY(), "Y")      → Age in years
=DATEDIF(A1, B1, "D")                   → Days between dates
```

---

#### 11. Text Functions

##### LEFT, RIGHT, MID
**Extract characters from text:**
```
=LEFT(text, num_chars)            → First N characters
=RIGHT(text, num_chars)           → Last N characters
=MID(text, start_num, num_chars)  → Middle characters

Examples:
=LEFT("Hello World", 5)           → "Hello"
=RIGHT("Hello World", 5)          → "World"
=MID("Hello World", 7, 5)         → "World" (start at 7, take 5)
```

##### UPPER, LOWER, PROPER
**Change case:**
```
=UPPER(text)                      → UPPERCASE
=LOWER(text)                      → lowercase
=PROPER(text)                     → Proper Case (First Letter Capital)

Examples:
=UPPER("hello")                   → "HELLO"
=LOWER("HELLO")                   → "hello"
=PROPER("hello world")            → "Hello World"
```

##### TRIM
**Remove extra spaces:**
```
=TRIM(text)                       → Remove leading/trailing/extra spaces

Example:
=TRIM("  Hello   World  ")        → "Hello World"
```

##### LEN
**Text length:**
```
=LEN(text)                        → Number of characters

Example:
=LEN("Hello")                     → 5
```

---

#### 12. Logical Functions

##### AND
**Syntax:** `=AND(logical1, logical2, ...)`  
**Purpose:** TRUE if ALL conditions are TRUE

**Example:**
```
=AND(A1>10, B1<20)                → TRUE if A1>10 AND B1<20
=IF(AND(A1>50, B1="Pass"), "Approved", "Rejected")
```

##### OR
**Syntax:** `=OR(logical1, logical2, ...)`  
**Purpose:** TRUE if ANY condition is TRUE

**Example:**
```
=OR(A1>100, B1>100)               → TRUE if A1>100 OR B1>100
=IF(OR(A1="Fail", B1="Fail"), "Retry", "Pass")
```

##### NOT
**Syntax:** `=NOT(logical)`  
**Purpose:** Reverses TRUE/FALSE

**Example:**
```
=NOT(A1>10)                       → TRUE if A1 is NOT > 10
=IF(NOT(A1=""), "Filled", "Empty")
```

---

#### 13. Statistical Functions

##### MEDIAN
**Syntax:** `=MEDIAN(number1, number2, ...)`  
**Purpose:** Middle value (50th percentile)

**Example:**
```
=MEDIAN(10,20,30,40,50)           → 30
=MEDIAN(A1:A10)
```

##### MODE
**Syntax:** `=MODE.SNGL(number1, number2, ...)`  
**Purpose:** Most frequently occurring value

**Example:**
```
=MODE.SNGL(5,10,5,15,5,20)        → 5 (appears most)
```

##### RANK
**Syntax:** `=RANK(number, ref, [order])`  
**Purpose:** Rank of number in list (1=highest or lowest)

**Example:**
```
=RANK(A1, A1:A10, 0)              → Rank (0=descending, 1=ascending)
```

---

#### 14. Rounding Functions

##### ROUND
**Syntax:** `=ROUND(number, num_digits)`  
**Purpose:** Round to specified decimal places

**Examples:**
```
=ROUND(3.14159, 2)                → 3.14
=ROUND(3.14159, 0)                → 3
=ROUND(1234.56, -2)               → 1200 (round to hundreds)
```

##### ROUNDUP
**Always round up:**
```
=ROUNDUP(3.14159, 2)              → 3.15
```

##### ROUNDDOWN
**Always round down:**
```
=ROUNDDOWN(3.14159, 2)            → 3.14
```

##### INT
**Round down to nearest integer:**
```
=INT(3.9)                         → 3
```

---

### Error Values in Formulas

| Error | Meaning | Cause |
|-------|---------|-------|
| #DIV/0! | Division by zero | Dividing by zero or empty cell |
| #N/A | Not available | VLOOKUP can't find value |
| #VALUE! | Wrong value type | Text in math formula (e.g., ="Hello"+5) |
| #REF! | Invalid reference | Deleted cell referenced in formula |
| #NAME? | Unrecognized name | Misspelled function name |
| #NUM! | Invalid number | Formula result too large, or invalid argument |
| #NULL! | Incorrect range | Space instead of comma (e.g., SUM(A1 B1)) |
| ##### | Column too narrow | Widen column to see value |

**Debugging:**
- Check formula in formula bar
- Verify cell references
- Use **Evaluate Formula** (Formulas tab) - step through calculation
- **Trace Precedents/Dependents** - show which cells affect formula

---

## 5. Creating Graphs (Charts)

### What is a Chart?
**Visual representation** of data in graphical form. Makes data easier to understand and compare.

---

### Types of Charts

#### 1. Column Chart
**Description:** Vertical bars representing values

**Best for:**
- Comparing values across categories
- Showing changes over time (few time periods)

**Example:** Sales by product, monthly revenue

**Subtypes:**
- **Clustered Column:** Multiple series side-by-side
- **Stacked Column:** Series stacked on top
- **100% Stacked:** Shows percentages

---

#### 2. Bar Chart
**Description:** Horizontal bars (sideways column chart)

**Best for:**
- Long category names (more room)
- Ranking (top 10 products)

**Example:** Survey results, product ratings

---

#### 3. Line Chart
**Description:** Points connected by lines

**Best for:**
- Trends over time (many time periods)
- Continuous data

**Example:** Stock prices, temperature trends, website traffic

**Subtypes:**
- **Line:** Simple line
- **Line with Markers:** Points highlighted
- **Stacked Line:** Multiple lines stacked

---

#### 4. Pie Chart
**Description:** Circle divided into slices (percentages)

**Best for:**
- Parts of a whole (must total 100%)
- Few categories (2-6 ideal, max 8)

**Example:** Market share, budget allocation, survey responses (Yes/No/Maybe)

**Subtypes:**
- **Pie:** Standard circle
- **Exploded Pie:** Slices pulled out
- **Doughnut:** Pie with hole (can show multiple series)

**Limitations:**
- Hard to compare similar values
- Not good for many categories
- Avoid if values don't sum to 100%

---

#### 5. Area Chart
**Description:** Line chart with filled area below

**Best for:**
- Cumulative totals over time
- Showing magnitude of change

**Example:** Total sales accumulation, population growth

**Subtypes:**
- **Area:** Overlapping areas
- **Stacked Area:** Areas stacked
- **100% Stacked:** Percentage contribution

---

#### 6. Scatter (XY) Chart
**Description:** Points plotted on X and Y axes

**Best for:**
- Correlation between two variables
- Scientific data

**Example:** Height vs. weight, temperature vs. ice cream sales

**Trendline:** Add to show relationship (linear, exponential, polynomial)

---

#### 7. Other Chart Types

**Combo Chart:** Combine two types (e.g., column + line)  
**Histogram:** Frequency distribution  
**Waterfall:** Show cumulative effect of positive/negative values  
**Funnel:** Sales pipeline stages  
**Treemap:** Hierarchical data (rectangles)  
**Sunburst:** Hierarchical pie chart  
**Box & Whisker:** Statistical distribution  

---

### Creating a Chart

#### Step-by-Step Process

**1. Select Data:**
- Highlight data range (including headers)
- Include row and column labels

**2. Insert Chart:**
- Insert tab → Charts group
- Choose chart type
- Or: Insert → Recommended Charts (Excel suggests)

**3. Chart Appears:**
- Chart inserted on worksheet
- **Chart Tools** appear (Design and Format tabs)

**4. Move Chart:**
- Click chart border
- Drag to new location
- Or: Chart Design → Move Chart → New Sheet (dedicated chart sheet)

**5. Resize Chart:**
- Click chart
- Drag corner handles (hold Shift for proportions)

---

### Chart Elements

#### Chart Title
- **Position:** Top, center
- **Edit:** Click title, type new text
- **Remove:** Chart Design → Add Chart Element → Chart Title → None

#### Axis Titles
- **Horizontal (X-axis):** Category labels (e.g., "Months")
- **Vertical (Y-axis):** Value description (e.g., "Sales ($)")
- **Add:** Chart Design → Add Chart Element → Axis Titles

#### Legend
- **Purpose:** Identifies data series by color/pattern
- **Position:** Right, top, bottom, left
- **Edit:** Click to select, drag to move
- **Format:** Change font, border, background

#### Data Labels
- **Purpose:** Show exact values on chart
- **Position:** Center, inside end, outside end, above, below
- **Add:** Chart Design → Add Chart Element → Data Labels
- **Format:** Number format, font size

#### Gridlines
- **Purpose:** Help read values
- **Types:** Major (main divisions), Minor (subdivisions)
- **Horizontal/Vertical:** Y-axis or X-axis
- **Add/Remove:** Chart Design → Add Chart Element → Gridlines

#### Data Table
- **Purpose:** Show data below chart
- **Add:** Chart Design → Add Chart Element → Data Table

#### Trendline
- **Purpose:** Show trend in data
- **Types:** Linear, exponential, logarithmic, polynomial, moving average
- **Add:** Click data series → Add Trendline
- **Options:** Display equation, display R-squared (correlation)

---

### Formatting Charts

#### Chart Styles
- **Quick Styles:** Chart Design → Chart Styles gallery
- Predefined color schemes and effects
- One-click professional look

#### Change Colors
- Chart Design → Change Colors
- Choose color scheme
- Matches document theme

#### Chart Type
- **Change:** Chart Design → Change Chart Type
- Switch between column, bar, line, etc.
- Can convert if data suits new type

#### Format Elements
- **Select element:** Click chart element (title, axis, bars, etc.)
- **Format pane:** Right-click → Format [Element]
- **Options:**
  - **Fill:** Solid, gradient, pattern, picture
  - **Border:** Line color, width, style
  - **Effects:** Shadow, glow, 3D
  - **Font:** Size, color, bold

#### 3D Charts
- Add depth and perspective
- Chart Design → Change Chart Type → 3D options
- **Warning:** Can distort perception (use carefully)
- **3D Rotation:** Format Chart Area → Effects → 3D Rotation

#### Data Series Formatting
- Click bar/line/slice
- Change fill color
- Add effects (shadow, glow)
- **Gap Width** (column/bar): Spacing between bars
- **Overlap** (clustered): Bars overlap or separate

---

### Chart Design Best Practices

✅ **Choose right chart type:** Match data to chart  
✅ **Clear title:** Describe what chart shows  
✅ **Label axes:** Specify units (dollars, %, etc.)  
✅ **Readable fonts:** Large enough (10+ pt)  
✅ **Meaningful colors:** Consistent, not random  
✅ **Avoid 3D (usually):** Can mislead (harder to read exact values)  
✅ **Limit data series:** 3-5 series max (avoid clutter)  
✅ **Simple is better:** Don't over-decorate  
✅ **Data labels (if needed):** Show exact values if important  
✅ **Legend placement:** Where it doesn't cover data  

---

### Updating Charts

#### Data Changes
- **Automatic update:** Chart updates when data changes
- Edit cells → chart reflects new values instantly

#### Add Data
- Click chart → Chart Design → Select Data
- Add new series or edit range

#### Remove Data Series
- Select Data → Select series → Remove

#### Switch Row/Column
- Chart Design → Switch Row/Column
- Swap what's on X-axis and in legend

---

## Quick Revision Summary

### Spreadsheet Basics
✅ **Components:** Workbook → Worksheets → Cells (rows × columns)  
✅ **Cell reference:** Column + Row (e.g., B5)  
✅ **Range:** A1:D10 (top-left : bottom-right)  
✅ **Formulas:** Start with =, use operators (+, -, *, /, ^)  

### Editing
✅ **Enter data:** Click cell, type, press Enter/Tab  
✅ **Edit:** Double-click cell or edit in formula bar  
✅ **AutoFill:** Drag fill handle (series, formulas)  
✅ **Copy/Cut/Paste:** Ctrl+C / Ctrl+X / Ctrl+V  
✅ **Find/Replace:** Ctrl+F / Ctrl+H  
✅ **Undo/Redo:** Ctrl+Z / Ctrl+Y  

### Formatting
✅ **Number:** Currency, percentage, date, fraction  
✅ **Font:** Bold (Ctrl+B), Italic (Ctrl+I), Underline (Ctrl+U), size, color  
✅ **Alignment:** Left/Center/Right, Wrap Text, Merge Cells  
✅ **Borders:** All borders, bottom border (for totals)  
✅ **Conditional Formatting:** Highlight cells, data bars, color scales, icon sets  

### Formulas & Functions
✅ **=SUM(range):** Add numbers  
✅ **=AVERAGE(range):** Calculate mean  
✅ **=MAX(range) / =MIN(range):** Highest/Lowest  
✅ **=COUNT(range):** Count numbers  
✅ **=IF(test, true, false):** Conditional logic  
✅ **=VLOOKUP(value, table, col, FALSE):** Lookup data  
✅ **=CONCATENATE(text1, text2):** Join text  
✅ **=TODAY():** Current date  
✅ **=SUMIF(range, criteria):** Conditional sum  

### Charts
✅ **Column:** Compare categories  
✅ **Line:** Trends over time  
✅ **Pie:** Parts of whole (percentages)  
✅ **Bar:** Horizontal comparison  
✅ **Scatter:** Correlation  
✅ **Insert → Charts → Choose type**  
✅ **Add:** Title, axis labels, legend, data labels, gridlines  

---

**Practice tip:** Create sample budgets, grade sheets, or sales trackers. Hands-on practice is the best way to master spreadsheets! Good luck with your exam on December 10th! 🎯📊**
