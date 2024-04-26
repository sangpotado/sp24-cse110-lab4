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