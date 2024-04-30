1. Line 12 will return 3 because we are asking the code to print out the index `i` after it has already iterated through the entire loop. Since there are 3 elements and we used zero based indexing, then the loop terminates when `i = 3` at which point it doesn't fit the for loop, and breaks. `i` remains to be 3 until the end of the code. 
2. Line 13 returns 150. This is because the last computed value for `discountedPrice` was for element 3, which is `300`, at a 50% discount. Therefore, the discounted price is 150 and it only returns this number. 
3. Line 14 returns 150. This is because the last computed value for `discountedPrice` is 150, due to the last element being `300`. Therefore, it uses this value to compute the final price, which is `150` multiplied by 100, rounded, and then divided by 100 again. 
4. This code shouldn't return anything visible on the command line but it should be returning the value of `discounted` if we printed it out. The code just runs all the way through without any errors on the command line though. 
5. Line 12 will throw a `ReferenceError`. This is because `i` is only defined inside the for loop block, so we can't get access to it outside that block. 
6. Line 13 also throws a `ReferenceError`. Again, `discountedPrice` is inside the for-loop block, making it inaccessible outside the loop.
7. This returns `150`. `finalPrice` was declared in the same block, so any updated values are updated there too, and we can reference it. 
8. Nothing is outputted, but it should be returning `discounted` and all the elements that are stored since we are logging all the final prices into this array. 
9. Line 11 will throw a `ReferenceError`. This is because `i` is only defined inside the for loop block, so we can't get access to it outside that block which is where we're calling it. 
10. This returns `3`. Since the length doesn't change and is constant, we are able to call it to return 3. 
11. This doesn't output anything on the command line, but it should be storing all discounted prices in an array and returning it. 
12. Notations:
    1.  `student.name`
    2.  `student['Grad Year']`
    3.  `student.greeting()`
    4.  `student['Favorite Teacher'].name`
    5.  `student.courseLoad[0]`
13. 