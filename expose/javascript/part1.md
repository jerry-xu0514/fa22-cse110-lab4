1. values added: 20
2. final result: 20
3. values added: 20
4. There is an error because the value is not accessable, since it is defined by the keyword let. The variable is defined inside of the if statement, and the second print/log statement is outside of the if statement, which means that the result variable is no longer accessible.
5. There is an error because we attempt to assign a value to a constant variable. At declaration result has already been given the value of 0, you cannot be changing that variable.
6. The result variable is not accessible outside of the if statement. The scope of const is within the block it was declared in.