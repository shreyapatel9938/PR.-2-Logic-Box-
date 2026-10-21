# PR.2  Logic Box:

A simple Python program that uses `match-case` to generate star patterns and analyze number ranges.

## Features:

1. **Generate a Pattern**: 
   * Creates a right-angled triangle star pattern (`*`) based on the number of rows entered.
   * **Validation**: Ensures the number of rows entered is a positive integer.

2. **Analyze a Range of Numbers**: 
   * Takes a starting and ending number, checks every number in the range, and identifies whether it is **Even** or **Odd**.
   * Calculates and prints the total sum of all numbers in that range.
   * **Validation**: Ensures the starting number is less than or equal to the ending number.

3. **Exit**: 
   * Safely exits the program loop with a goodbye message.

4. **Error Handling**: 
   * Features a fallback default case (`case _`) to catch invalid menu choices.