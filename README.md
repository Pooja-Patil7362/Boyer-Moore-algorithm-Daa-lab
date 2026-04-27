# Boyer-Moore Algorithm

## Problem
Search for a pattern in a given text using efficient string matching.

## Approach
- Compare pattern from right to left
- Use bad character heuristic to skip comparisons
- Shift pattern intelligently

## Time Complexity
- Best Case: O(n / m)
- Average Case: Sub-linear
- Worst Case: O(n * m)

## Space Complexity
- O(1)

## Example
Text: ABABDABACDABABCABAB  
Pattern: ABABCABAB  

Output: Pattern found at index 10