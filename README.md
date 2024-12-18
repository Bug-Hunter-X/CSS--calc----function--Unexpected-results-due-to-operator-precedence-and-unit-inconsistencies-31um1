# CSS `calc()` function: Unexpected layout issues
This repository demonstrates a common error when using the CSS `calc()` function: inconsistencies in units and operator precedence. The `bug.css` file shows an example of how incorrect usage can lead to unexpected layout. The `bugSolution.css` file shows how to correct the issue.

**Problem:** The `calc()` function doesn't always behave as expected when units are mixed (e.g., percentages and pixels) without clear operator precedence. Incorrect usage can result in misaligned or unexpectedly sized elements.

**Solution:** Ensure that you use consistent units within the `calc()` expression and properly use parentheses to dictate the order of operations. Avoid mixing percentages and pixels without explicit parentheses.