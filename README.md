# Data-entry-and-analysis-of-business-expenses
Update of daily and monthly business expenses

=SUMIFS($D$2:$D$1003; $B$2:$B$1003; $G2; $A$2:$A$1003; ">="&DATE(YEAR(TODAY()); MATCH(H$1; $F$2:$F$1003; 0); 1); $A$2:$A$1003; "<="&EOMONTH(DATE(YEAR(TODAY()); MATCH(H$1; $F$2:$F$1003; 0); 1); 0))
1. Enter the daily costs with a choice of cost category
2. Automatic adds up the cost per category and month
3. Displays charts by category and month
