1. `3` is printed in the terminal. after the loop, var `i` = 3, it got printed out when we call `console.log(i)`
2. `150` is printed in the terminal. at the final iteration of the loop, `var discountedPrice = 300 * (1- 0.5) = 150`
3. `150` is printed in the terminal. at the final iteration of the loop, `finalPrice = Math.round(discountedPrice * 100) / 100 = Math.round(150 * 100)/100 = 150`
4. nothing is printed out in the terminal, but the function does return `discounted = [ 50, 100, 150 ]` array. at each iteration, `finalPrice` is calculated from `prices[i]` and pushed to `discounted`.

5. error. ReferenceError: i is not defined. `i` was declared only for the loop, line 12 is out of scope of the loop and `i`
6. error. ReferenceError: discountedPrice is not defined. `discountedPrice` is in the loop. it is out of scope at line 13
7. `150` is printed in the terminal. `finalPrice` was declared within the function, line 14 call it within its scope
8. nothing is printed out in the terminal, but the function does return `discounted = [ 50, 100, 150 ]` array. at each iteration, `finalPrice` is calculated from `prices[i]` and pushed to `discounted`.
9. error. ReferenceError: i is not defined. `i` was out of scope
10. `3` is printed out in the terminal. because the length of `prices` is a const value 3
11. nothing is printed out in the terminal, but the function does return `discounted = [ 50, 100, 150 ]` array. at each iteration, `discountedPrice` is calculated from `prices[i]` and pushed to `discounted`. although `discounted` is a const variable, it means it can't be changed to point to another array object, it doesn't mean that the elements in the array can't be changed
12. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]

13. Arithmetic
    A. '32' integer converted to string
    B. 1 string converted to integer
    C. 3 ,null is considered nothing
    D. '3null' , null object converted to string
    E. 4, true is int 1
    F. 0, null object converted to false
    G. '3undefined' , object converted to string
    H. NaN, not a number
14. Comparison
    1.  true, 2 > 1
    2.  false, first integer of '12' is 1 < 2
    3.  true, string coverted to int, 2 == 2
    4.  false, different type
    5.  false, int 2 is not true/false value
    6.  true, most significant bit of 2 is 1
15. == and === both compare, but == ignores datatype, === checks datatatype
16. see file
17. [ 2, 4, 6 ] . as we iterate the input `array`, each element is modified by `callback` function, which is `doSomething`. So, the value of each element is multiplied by 2.
18. see file
19. 1 4 3 2