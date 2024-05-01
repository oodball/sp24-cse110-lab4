1. Line 12 will return 3 because we are asking the code to print out the index `i` after it has already iterated through the entire loop. Since there are 3 elements and we used zero based indexing, then the loop terminates when `i = 3` at which point it doesn't fit the for loop, and breaks. `i` remains to be 3 until the end of the code. 
2. Line 13 returns 150. This is because the last computed value for `discountedPrice` was for element 3, which is `300`, at a 50% discount. Therefore, the discounted price is 150 and it only returns this number. 
3. Line 14 returns 150. This is because the last computed value for `discountedPrice` is 150, due to the last element being `300`. Therefore, it uses this value to compute the final price, which is `150` multiplied by 100, rounded, and then divided by 100 again. 
4. This code shouldn't return anything visible on the command line but it should be returning the value of `discounted` if we printed it out, which is an array. The code just runs all the way through without any errors on the command line though. 
5. Line 12 will throw a `ReferenceError`. This is because `i` is only defined inside the for loop block, so we can't get access to it outside that block. 
6. Line 13 also throws a `ReferenceError`. Again, `discountedPrice` is inside the for-loop block, making it inaccessible outside the loop.
7. This returns `150`. `finalPrice` was declared in the same block, so any updated values are updated there too, and we can reference it. 
8. Nothing is outputted, but it should be returning `discounted` and all the elements that are stored since we are logging all the final prices into this array. 
9. Line 11 will throw a `ReferenceError`. This is because `i` is only defined inside the for loop block, so we can't get access to it outside that block which is where we're calling it. 
10. This returns `3`. Since the length doesn't change and is constant, we are able to call it to return 3. 
11. This doesn't output anything on the command line, but it should be storing all discounted prices in an array and returning it. 
12. Notations:
    <ol type="A">
    <li>student.name</li>
    <li>student['Grad Year']</li>
    <li>student.greeting()</li>
    <li>student["Favorite Teacher"].name </li>
    <li> student.courseLoad[0]</li>
    </ol>
13. Arithmetic: 
    1.  `32`. This is because integers map to their exact string representation, and we have `"3"` as a string, which means that `2` convrts to a string too. 
    2.  `1`. This is because the `-` operator is present. Therefore, `3` gets switched into an integer, and integer subtraction is performed. 
    3.  `3`. `null` is represented as `0`, so we're just adding 3 + 0. 
    4.  `3null`. SImilar logic to 1. 3 is a string, so it will convert the second part to a string as well, concatenating them. 
    5.  `4`. This is because `true` is represented by a 1, so we're adding 3 + 1. 
    6.  `0`. Both `false` and `null` are represented by 0, so 0 + 0 = 0. 
    7.  `3undefined`. Again similar logic to 1 and 4, performing string concatenation. 
    8.  `NaN`. We can't do this because `undefined` doesn't have a numeric representation. 
14. Comparison:
    1.  `true`. We can convert `2` to be an integer and then perform integer comparisons. 
    2.  `false`. We compare character by character here since they're both string types, so then it becomes false because 2 is not less thn 1. 
    3.  `true`. We convert one of the `2` to the same type as the other one,and then this becomes `true`. 
    4.  `false`. The types are not strictly the same. 
    5.  `false`. `true` evaluates to 1, and 1 is not equal to 2. 
    6.  `true` They both evaluate to 1. 
15. `==` only checks if they're the same and can convert to other data types. `===` is a strict checker that also checks for data type.
16. see file `part2-question16.js`
17. The result isn't shown in command line, but it should return a value with the array `[2, 4, 6]` in it. This is because we use the for loop to iterate through every element in the array, and then push a modified element from `doSomething`, which doubles the number. Then, that modified number gets pushed to the new array, and we get the end result. 
18. See `part2-question18.js`
19. We get the output `1 4 3 2` printed individually on different lines. I think this is due to the delay. We have 1 and 4 which are immediate, then 2 which has a 1 second delay, and then 3 with 0 ms, but it executes after 4. 