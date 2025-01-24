# CSS `calc()` Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to inconsistencies in units or the order of operations.  The `bug.css` file contains the problematic code, and `bugSolution.css` offers a solution.

The issue stems from how browsers parse and evaluate the expressions within `calc()`.  Incorrect unit usage or ambiguous ordering can lead to unexpected layout changes.  The solution focuses on clarifying the calculation by ensuring consistent units and enforcing the correct order of operations through parentheses.