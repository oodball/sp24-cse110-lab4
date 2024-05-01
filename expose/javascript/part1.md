1. line 9 prints 20. 
2. Line 13 prints 20. 
3. 20. 
4. There is a reference error. This is because `let` is only declared within the `if` statement block, so trying to access it in the `console.log` means it will call from outside the `if` block. 
5. I believe this is an error because you are trying to change a `const` variable, whose whole point is to declare it so it can't be changed. 
6. This is the same error as number 5. We are trying to change a constant variable that can't be changed. 