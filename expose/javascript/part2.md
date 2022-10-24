1. the var i declared in the declaration of the for loop uses the var keyword, thus meaning that its scope is a function scope. Thus, line 12 will execute as normal, and by the endo fthe for loop, i takes on its final value 3, thus, 3 is printed at line 12.
2. 150, similar to the last question, the discountedPrice variable is declared using the var scope, and the last value in which the discounted price will hold will be 150
3. 150, similar to the last questsion again, the last value that finalPrice will take on will be 150.
4. the function will return a list containing the values [50,100,150], since we are effectively dividing each value by half and pushing them into the list discounted, and then returning that list.
5. It causes an error. the variable i will not be accessible outside of the for loop, since that is where it is declared and the let keyword means that it has a block scope. 
6. It causes an error. The variable discountedPrice is defined by let, and it has a block scope, defined in the for loop, it will not be accessible outside.
7. 150, final price, as it was declared in the fucntion and outside, before the for loop, it is accessible both inside and outside the for loop, thus no errors persist, and the function works as intended and gives 150, the correct value.
8. [50, 100, 150], the let scope defined does not affect how the function runs as compared to var, 
9. Similar to question 5, the variable i will not be accessible outside of the for loop, thus an error will persist.
10. 3, since we are looking for the length of prices, and which happens to be 3, the answer will be 3. The scope of declaration being const here does not really affect much as we never manipulate or assign the variable, we are simply reading it.
11. This function still returns [50, 100, 150], despite the array discounted being defined as a const, we are only defining the reference to be constant, and not the values, adding, deleting, changing values within the array. Thus, no error, and the function returns as expected.
12. Writing notaions:
    1. student.name
    2. student["Grad Year"]
    3. student.greeting()
    4. student["Favorite Teacher"].name
    5. student.courseLoad[0]
13. Arithmetic
    1. 32
    2. 1
    3. 3
    4. 3null
    5. 4
    6. 0
    7. 3undefined
    8. NaN
14.  Comparison
    1.  true
    2.  false
    3.  true
    4.  false
    5.  false
    6.  true
15. === checks the equality between the two variables without any type conversion, in other words, == would apply type conversion first before checking for equality, true might be converted to 1 or vice versa, while this operation would not happen in ===.
17. The result will be an array with the contents [2,4,6], we are simply applying the doSomething function to each of the values inside of the array [1,2,3], and doSomething just returns the value multiplied by 2, and thus we just mulitply each value in the original arguement by 2, thus reaching our answer.
19. 
1
4
3
2
