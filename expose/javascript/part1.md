1. values added:  20
2. values added:  20
3. values added:  20
4. **Error:** *ReferenceError: result is not defined.*
It's because the variable result is declared within the if block using let, which means it has block scope and is only accessible within that block. Therefore, trying to access result on line 13 - outside of its block, results in a ReferenceError.
5. **Error:** *result = num1 + num2; TypeError: Assignment to constant variable.*
It's because const declare a constant refresnce to a value, which means it cannot be changed once it's assigned.
6. **Error:** *result = num1 + num2; TypeError: Assignment to constant variable.*
It's because const declare a constant refresnce to a value, which means it cannot be changed once it's assigned. Also it has the same scope as the let keyword so it has scope problem also, cannot be access outside the block it's declared.