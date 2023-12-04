Code fails 3 object test cases and 3 proto test cases.
Known error is when proto is used within a while loop, it 
causes an infinite loop and reaches the max recursion limit 
for Python.
