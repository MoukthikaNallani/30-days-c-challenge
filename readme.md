1. Start.
2. Declare validCount, smallCount, mediumCount and largeCount as int, and amount, validTotal, smallTotal, mediumTotal, largeTotal and average as float.
3. Set all counts and totals to 0.
4. Repeat using a do-while loop:
a. Read the expense amount.
b. If amount < 0, display an error message and ignore the amount.
c. Else if amount > 0 (valid expense): if amount < 100, it is Small (smallCount++ and smallTotal += amount); else if amount < 500, it is Medium (mediumCount++ and mediumTotal += amount); otherwise it is Large (largeCount++ and largeTotal += amount). Then increase validCount by 1 and add the amount to validTotal.
d. Stop repeating when amount is 0 (0 is not counted or added).
5. If validCount is 0, display "No valid expenses were entered".
6. Otherwise, calculate average = validTotal / validCount and display the number and total of valid expenses, the count and total of Small, Medium and Large expenses, and the average expense.
7. Stop.
