1. "3" will be printed on the console since i is a var that can be accessed at line 12.
2. "150" will be printed on the console since discoutedPrice is a var that can be accessed outside the for loop.
3. "150" will be printed on the console since finalPrice is a var that can be accessed outside the for loop.
4. [50, 100, 150] will be printed since discounted is a var that can be accessed outside the for loop.
5. The console will print "3" since i can be accessed from line 12.
6. The code causes an error at line 13 since discountedPrice is a let that cannot be accessed outside the for loop.
7. The console will print "150" since finalPrice is a let that can be accessed from line 14.
8. [50, 100, 150] will be returned since the for loop successfully adds 3 numbers to the discounted array.
9. "3" will be printed since i is a let that can be accessed from line 11.
10. "3" will be printed since length is a const that can be access from line 12.
11. [50, 100, 150] will be returned since the for loop successfully adds 3 numbers to the discounted array.
12. 
    1.  alert( student.name );
    2.  alert( student["Grad Year"] );
    3.  student.greeting();
    4.  alert( student["Favorite Teacher"]["name"] );
    5.  alert( student["courseload"][0] );

13. Arithmetic
    1.  "32", since 2 converts to a string.
    2.  "1", since 3 converts to a number when doing arithmetic.
    3.  "3", since null converts to 0 numerically.
    4.  "3null", since null converts to a string when added to a string.
    5.  "4", since true converts to 1 numerically.
    6.  "0", since false and null both convert to 0 numerically.
    7.  "3undefined", since undefined is converted to the string "undefined" when added to a string.
    8.  "NaN", since undefined becomes NaN when performing arithmetic operations.

14. Comparison
    1.  True, since the string "2" becomes a number 2.
    2.  False, since string "2" does not come before string "12" lexicographically.
    3.  True, since the string "2" becomes the number 2.
    4.  False, since the === operator checks equality without type convertsion.
    5.  False, since true converts to 1 and string "2" converts to the number 2.
    6.  True, since a non-zero number converted to a boolean is true.

15. The == operator checks for equality of two variables. If the variables are of different types, both are converted to numbers and then compared. Like the == operator, the === operator checks whether two variables are equal. However, the === operator only returns true if the datatypes of the two variables are equal as well.

17. The result of the function call is [2, 4, 6]. The modifyArray function takes an array and returns a new array with each element of the original array modified by a given callback function. In our case, that callback function is doSomething, which returns the given number multiplied by 2. Therefore, the [1, 2, 3] is returned by the numbers all doubled.
19. The output of the code is:
1
4
3
2