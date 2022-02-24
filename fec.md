# Data Analysis 
## Data Cleanup
1. Copy data onto Google Sheets and open Sheet 2
2. Sort by donor name A to Z
3. Follow Google Sheets cleanup suggestions
4. Change SONNYWALE to SUNNYVALE
5. Change NEW YORKROOK to NEW YORK 
6. Change ATHERTONO to ATHERTON
7. **NOTE** 12 duplicated rows found, need fact checking whether it's multiple transactions a day or data mistakes 

## Q1 
1. Freeze 1st row
2. Create pivot table
3. Industry for rows, Party for Columns, Amount for Values
4. Use =max() function to find the highest doenr industry 
5. !['Pivot table 1'](/Pivottable1.png)
6. Highest contributor to D is Media Entertainment industry, of $1,880,000.00
7. Highest contributor to R is Republican/Conservative industry, of $7,514,000.00
8. !['Solution Q1'](/SolutionQ1.png)

## Q2
1. Sort A to Z to find Misc. Business sector 
2. Copy that onto new sheet
3. Filter Party column for D
4. Copy that onto new sheet
5. Use =sum() fucntion to find total amoount
6. Total amount is $3,520,000.00 for Misc. Business sector contribution to Democratic Party
7. Filter City column for Miami Lakes
8. 2 results forn Miami Lakes, FL, both by Windmere Corp
