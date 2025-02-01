# Uncommon Error in Python Function
This repository demonstrates an uncommon error that can occur in Python functions involving division: a ZeroDivisionError when both inputs are zero.

The function `function_with_uncommon_error` handles cases where either input is zero, but doesn't explicitly check for the scenario where both are zero.
This leads to a ZeroDivisionError exception.

The `bugSolution.py` file shows the corrected function which addresses this edge case, preventing the exception.