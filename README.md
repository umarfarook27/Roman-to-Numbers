# Roman-to-Numbers
Identify 
Roman Numerals:

Roman numerals are composed of seven basic symbols: I, V, X, L, C, D, and M, representing the values 1, 5, 10, 50, 100, 500, and 1000, respectively.
The numbers are formed by combining these symbols and following certain rules.
A smaller numeral in front of a larger numeral subtracts its value (e.g., IV represents 4, where I (1) is subtracted from V (5)).
In contrast, when a smaller numeral comes after a larger numeral, their values are added (e.g., VII represents 7, where I (1) is added to VI (6)).
Roman to Number Conversion:

Start from the leftmost symbol:

Compare the values of adjacent symbols.
If the value of the symbol on the left is smaller or equal, add its value to the result.
If the value of the symbol on the left is greater, subtract its value from the result.
Repeat the process:

Move to the next pair of symbols and continue the comparison.
Add or subtract accordingly:

Keep adding or subtracting the values based on the comparison until you reach the rightmost symbol.
Sum the values:

The final result is the sum of all the values obtained in the process.
Example:

Consider the Roman numeral "XIV."
Start from the leftmost symbol: X (10).
The next symbol is I (1), which is smaller, so add 1 to the result.
Move to the next pair: IV (4).
I (1) is subtracted from V (5), resulting in 4.
Sum the values: 10 (X) + 1 + 4 = 15.
