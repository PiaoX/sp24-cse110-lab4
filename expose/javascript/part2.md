1. 3
2. 150
3. 150
4. It will return an array of discounted prices because the function *discountPrices* takes in an array of prices and a discount percentage, then calculates the discounted price for each item in the array and stores them in a new array called *discounted*. It then returns this array of discounted prices.
5. **Error:** *ReferenceError: i is not defined*
Since *i* is declared with let in the *for loop* which has a block scope and cannot be accessed outside the scope.
6. **Error:** *ReferenceError: discountedPrice is not defined*
Since *discountedPrice* is declared with let in the *for loop* which has a block scope and cannot be accessed outside the scope.
7. 150
At line 14, it will print the final discounted price of the last item in the prices array. This is because *finalPrice* is declared inside the function and called inside the function which does not have a reference error so it will calculated in the loop and output the discounted price of the last item in the prices array.
8. [ 50, 100, 150 ]
The function will return the array *discounted*. Each value in this array represents the discounted price of each item in the prices array after applying a 50% discount.
9. **Error** 
This is because the variable i is declared using let inside the for loop, which means it's only accessible within the block scope of that loop. Outside the loop, i is not defined.
10. 3
At line 13, the code will log the length of the prices array, in this case is 3. Since length is declared using const, its value remains constant throughout the execution of the function.
11. [ 50, 100, 150 ]
The function will return an array containing the discounted prices of the items in the prices array after applying the discount.

# Data Types
12. A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];

# Basic Operators & Type Conversion 
13. A. 32 This is because the + operator concatenates strings, so '3' is concatenated with 2, resulting in '32'.
    B. 1 The - operator tries to convert strings to numbers, so '3' is converted to the number 3, and then subtraction is performed.
    C. '3null'. Similar to the first example, the + operator concatenates strings, so '3' is concatenated with the string representation of null.
    D. 4. In arithmetic operations, true is treated as 1, so 1 + 3 equals 4.
    E. 0. Similar to the previous example, false is treated as 0, so 0 + 0 equals 0.
    F. '3undefined'. As with null, undefined is converted to its string representation when concatenated with a string.

14. A. true. Strings are converted to numbers in a comparison, so '2' becomes 2, which is greater than 1.
    B. false. When comparing strings, they are compared character by character from left to right, so '2' is greater than '1', resulting in false.
    C. true. The == operator performs type conversion, so 2 is converted to a string and then compared to '2', resulting in equality.
    D. false. The === operator checks both value and type without type conversion, so since 2 and '2' have different types, the result is false.
    E. true. The true boolean value is coerced to the number 1, so 1 == 2 returns false.
    F. false. The Boolean(2) expression returns true, but since true and 1 are of different types, the result is false.

15. == performs type coercion before comparison, which means it tries to convert operands to the same type before comparing. === is strict equality, it compares both value and type without coercion. 

# Loops
16. part2-question16.js

# Functions
17. [ 2, 4, 6 ]
When modifyArray([1,2,3], doSomething) is called, it passes the array [1,2,3] and the doSomething function as arguments to modifyArray. Inside modifyArray, for each element of the array, doSomething is called. doSomething doubles the value of each element. The modified values are then stored in a new array. Finally, the new array [2, 4, 6] is returned as the result of the function call.

# setInterval(), setTimeout(), clearTimeout()
18. part2-question18.js
19. 
`
1
4
3
2
`