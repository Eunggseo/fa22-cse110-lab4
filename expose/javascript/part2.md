1. It will print `3`, since variable i is to count the length of the prices array which is 3.
2. It will print `150`. It is the value of `discountedPrice`.
3. It will print `150`, the value of `finalPrice`. Since there is no need for `discountedPrice` to be rounded to the nearset integer.
4. The function will return [50, 100, 150].The function loops through each element in the prices array and calculates the discounted price by multiplying it by 0.5 (since the discount is 50%). The resulting discounted price is then appended to the discounted array. Therefore, the final discounted array would be equivalent to 0.5 times the value of each of the initial prices, which gives us [50, 100, 150] for the original prices of [100, 200, 300].
5. Error, because i is not defined in the scope.
6. Error, because `iscountedPrice` is not defined in the scope.
7. It will print `150`, This is because the `finalPrice` object is declared outside of the for loop, but within the `getPrice` function, which means it has function scope and can be accessed by any code within the function.
8. The function will return [50, 100, 150]. Because the variables i, num, and result are all declared inside the for loop block, which means they have block scope and are only accessible within the for loop. Therefore, when the function returns the prices array, it will contain the values [50, 100, 150] regardless of whether let or var is used to declare the variables in the for loop.
9. Error, because i is not defined in the scope.
10. It print  `3`, since it was initialized as a `const` value which is the length of the prices 3.
11. It will return [50, 100, 150], since `discounted` is declared using `const`, we are still able to modify its contents by adding elements to it. This allows us to correctly compute the discounted prices and add them to the discounted array during each iteration of the for loop. 
12. a.`student.name`<br>
b.`student['Grad Year']`<br>
c.`student.greeting()`<br>
d.`student['Favorite Teacher'].name`<br>
e.`student.courseLoad[0]`<br>
13.  a. `32`, 2 is concatenated to 3.<br>
b. `1` , 3 is treated as an integer, and do the subtraction:3-2=1.<br>
c. `3`,  null is 0, and we add 0 get 3.<br>
d. `3null`, null is a string 'null', and then used to concatenate with 3.<br>
e. `4`, true is treated as 1, 3+1=4<br>
f. `0` both are treated as 0s to add.<br>
g. `3undefined`, undefined is treated as a string here<br>
h. `NaN`, 3 is treated as integer 3 but undefined is treated as NaN, NaN cannot be calculated which will return a NaN<br>
14.    true, '2' is treated as an integer, 2>1 returns true<br>
false, '2' and '12' are treated as integers, 2<12, returns false.<br>
true, '2' is treated as an integer, 2==2, returns true.<br>
false, first '2' is a string and the second '2' is an integer, types are not equal so return false.<br>
false, the integer of true is 1, everything other than 1 is false<br>
true, e in boolean everything other than 0 is true<br>
15.   == performs a loose comparison by allowing type conversion, while === performs a strict comparison without type conversion.
16.   [part2-question16.js](/Users/wenyuzhong/fa22-cse110-lab4/expose/javascript/part2-question16.js)
17.   It will create a new array: [2,4,6]. it executes a for-loop the length of the array times.  Each number is multiplied by two.
18.   [part2-question18.js](fa22-cse110-lab4/expose/javascript/part2-question18.js)
19.  It will print: <br>
1<br> 
4<br> 
3<br> 
2<br> 