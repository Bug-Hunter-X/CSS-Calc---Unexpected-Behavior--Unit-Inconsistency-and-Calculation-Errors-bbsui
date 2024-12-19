# CSS Calc() Unexpected Behavior

This repository demonstrates an uncommon issue with the CSS `calc()` function: unexpected results caused by inconsistent units or invalid calculations.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides the corrected version.

**Problem:**
The `calc()` function, while powerful, can be problematic if units aren't handled consistently or if the calculation itself is invalid.  The resulting layout can be unpredictable and lead to difficult-to-debug rendering inconsistencies.

**Solution:**
Ensure consistent units within the `calc()` expression and thoroughly test the expression's validity to avoid unexpected results.