# Creating-an-executive-data-summary
This worksheet is called Summary and is in the workbook Quarter One Report.xlsx. In this worksheet, I needed to complete the following actions:

Create formulas that show the total quarter-one sales for both 2022 and 2023.

Create formulas that show the percentage increase in sales in 2023. 

And break down these totals by month with the use of further calculations.
**Step 1: Add and format headings.**
First thing I needed to do is reformat the spreadsheet
column A and column F needed to be widened to fit the entries 
A1 and A10 needed to be merged and centered
I added a new column after column E and named it Product ID
I made B5, C5, D5, B11, C11, and D11 bold and turned on wrap text

**Step 2: Customize and reorganize how the data is displayed.**
I input **=PROPER(G2)** into H2 to transfer the information from column G. I then deleted column G as it was no longer needed turning column H into G
I then sorted the dates oldest to newest
I deleted column E as it was not needed 
I froze the top row and everything left of E2
**Step 3: Use formulas to create new row information**
I used the **=MONTH** and **=YEAR** formulas to get the month and the year in column J and colomn K
in P2 I used to find  retail price times the order quantity
I multiplied the number of orders and how much the orders cost and put that into column N order total before taxes 
To find the order total I used the formula
**=IF(N2>2000,N2*0.05,0)** 

if the total was over 2000 it would be multiplied by .05 if not it would not be multiped by .05

**Step 4: Create formulas to calculate and compare the profit margin across two years.**
I used the formula **=SUMIF(J2:J246,2022,P2:P246)** to calculate the total earnings of 2022 and **=SUMIF(J2:J246,2023,P2:P246)** for 2023
The following formulas were used to calculate the sales from January, Febuary, and March of 2022 and 2023 
2022:
**=SUMIF($I$2:$I$33,1,$P$2:$P$33)**
**=SUMIF($I$34:$I$67,2,$P$34:$P$67)**
**=SUMIF($I$68:$I$103,3,$P$68:$P$103)**
2023:
**=SUMIF($I$104:$I$148,1,$P$104:$P$148)**
**=SUMIF($I$149:$I$194,2,$P$149:$P$194)**
**=SUMIF($I$195:$I$246,3,$P$195:$P$246)**
The following formulas were used to calculate the increase of sales between 2022-2023 and compares the increase in sales between January Febuary and March of 2022 and 2023.
**=(C6-B6)/B6**
**=(C12-B12)/B12**
**=(C13-B13)/B13**
**=(C14-B14)/B14**
