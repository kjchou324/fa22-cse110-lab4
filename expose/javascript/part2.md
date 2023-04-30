# Part 1

### Question 1
Line 9 prints `values added: 20`.

### Question 2
Line 13 prints `final result: 20`.

### Question 3
Line 9 prints `values added: 20`.

### Question 4
Line 13 would return an error. Since `result` is defined inside the if statement, it is only defined in that block. Therefore, since line 13 is outside that block, `result` is not defined there.

### Question 5
The code would return an error since `result` is defined as a const, but then gets reassigned on line 7.

### Question 6
The code would return and error since `result` is defined as a const, but then gets reassigned on line 7.

# Part 2

### Question 1
At line 12 the code will print `3`. This is because `i` is defined to be in the function scope, and the for loop increments until `i` is no longer less than `prices.length`, where `prices` has length 3.

### Question 2
At line 13 the code will print `150`. This is because during the final loop of the for loop when `i` is `2`, `discountedPrice` gets assigned as `prices[2] * (1 - 0.5)` which is 300 * 0.5 = 150.

### Question 3
At line 14 the code will print `150`. This is because `finalprice` is set to `Math.round(discountedPrice * 100) / 100` and `discountPrice` is `150` as explained above.

### Question 4
This function returns the the array `[50, 100, 150]`. `discounted` gets initiated at the beginning, and then is filled with the values `50`, `100`, and `150` in the for loop.

### Question 5
This code causes an error since `i` is defined in the scope of the for loop, and therefore isn't defined outside and on line 12.

### Question 6
This code causes an error since `discountedPrice` is defined in the scope of the for loop on line 7, and therefore isn't defined outside and on line 13.

### Question 7
At line 14 the code will print `150` since `finalprice` is defined in the same scope as the call on line 14. It is also set to the value `150` for the same reason explained in question 3.

### Question 8
This function returns the array `[50, 100, 150]`. `discounted` gets initiated at the beginning, and then is filled with the values `50`, `100`, and `150` in the for loop.

### Question 9
This code causes an error since `i` is defined in the scope of the for loop, and therefore isn't defined outside and on line 11.

### Question 10
At line 12 the code will print `3` since `length` is defined in the scope of the print statement, and `prices.length` is 3.

### Question 11
The function returns the array `[50, 100, 150]` as `discounted` is intialized, filled with the values `50`, `100`, and `150` in the for loop, and is returned at the end.

### Question 12
A. `student.name` \
B. `student['Grad Year']` \
C. `student.greeting()` \
D. `student['Favorite Teacher'].name` \
E. `student.courseLoad[0]`

### Question 13
A. '32'. 2 gets converted to the string '2', so '3' + '2' = '32'. \
B. 1. '3' gets converted to the number 3, and 3 - 2 = 1. \
C. 3. null gets converted to the number 0, and 3 + 0 = 3. \
D. 3null. null gets converted to the string 'null', so '3' + 'null' = '3null'. \
E. 4. true gets converted to the number 1, and 1 + 3 = 4. \
F. 0. false gets converted to the number 0 and null gets converted to the number 0, so 0 + 0 = 0. \
G. '3undefined'. undefined gets converted to the string 'undefined', so '3' + 'undefined' = '3undefined'. \
H. NaN. undefined gets converted into NaN and '3' gets converted to 3, therefore 3 - NaN = NaN.

### Question 14
A. true. '2' gets converted to the number 2, and 2 > 1 is true. \
B. false. the string '2' is not lexicographically smaller than '12'. \
C. true. '2' gets converted to the number 2, and 2 == 2 is true. \
D. false. strict equality means '2' stays as a string, therefore the number 2 is not equal to the string '2'. \
E. false. true gets converted to the number 1, and 1 == 2 is false. \
F. true. Boolean(2) gets converted to true and is of type boolean, therefore true === true is true.

### Question 15
`==` checks the equality between two values without comparing the types, so it would convert the types as needed. However, `===` checks equality while also checking the types, so if the two things checked are different types it wouldn't convert them and would be false.

### Question 16
[part2-question16.js](part2-question16.js)

### Question 17
`modifyArray([1,2,3], doSomething)` returns the array `[2, 4, 6]`. We start by defining `newArr` as an empty array. Then we use the for loop and iterate through i = 0, i = 1, and i = 2. We pass the parameter `doSomething` as callback, so each time we push `callback(array[i])` we make a call to the function `doSomething` with the parameter `array[i]`.
This gives us the values `2`, `4`, and `6` which end up in `newArr` which is returned.

### Question 18
[part2-question18.js](part2-question18.js)

### Question 19
```
1
4
3
2
```