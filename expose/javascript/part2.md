1. 3, i is function scoped with var, so it is defined in line 12. At this point, it should be equal to prices.length, which would be 3 based on the input.
2. 150, discountedPrice is function scoped with var, so it is defined in line 13. At this point, it would be equal to the final discounted price, which is 50% of 300 or 150.
3. 150, finalPrice is function scoped with var, so it is defined in line 14. At this point, finalPrice is equal to the rounded final discountPrice, which is 150.
4. [50, 100, 150], discount is function scoped with var, so it is defined in the return statement. At this point, this is the array of discounted prices, so applying a 50% discount to the input of [100, 200, 300] gives [50, 100, 200]. 
5. Error. This is because i is declared with let within the for loop block, so it is not defined in line 12.
6. Error. This is because discountedPrice is declared with let within the for loop block, so it is not defined in line 13.
7. 150, finalPrice is block scoped with let, but is in the same block as line 14 (not part of the for loop), so it is defined. At this point, this is the final rounded discountPrice, or 150.
8. [50, 100, 150], discount is block scoped with let, and is in the same block as the return statement. It will return the same output as question 4.
9. Error. This is because i is declared with let within the for loop block, so it is not defined in line 11.
10. 3, length is block scoped with const, and is in the same block as line 12 so it is defined. It is equal to the length of the input array, which is 3.
11. [50, 100, 150], discounted is block scoped with const, and is in the same block as the return statement. It will return the discounted prices as an array - we can still modify the existing const, just not reassign it. So the output will be same as #4 and #8.
12. Shown below:
- A. student.name
- B. student['Grad Year']
- C. student.greeting()
- D. student['Favorite Teacher'].name
- E. student.courseLoad[0]
13. Shown below:
- A. '32', '3' is a string so plus does string concat with 2 convereted to string.
- B. 1, minus is arthimetic so 3 is converted to number.
- C. 3, null is 0 in arithmetic.
- D. 3null, '3' is a string so plus does string concat, null is converted to string.
- E. 4, true is 1 in arithmetic.
- F. 0, both false and null are 0 in arithmetic.
- G. 3undefined, '3' is a string so plus does string concat, undefined is converted to string.
- H. NaN, minus is arithmetic, but undefined is not a number.
14. Shown below:
- A. True, 2 is convereted to number.
- B. False, strings compared lexiographically, 2 comes after 1.
- C. True, == does not check type, so '2' is converted to number.
- D. False, === does check type.
- E. False, true is considered 1.
- F. True, 2 as a boolean is true as a non zero number.
15. == checks equality of just value, so different types will be converted to a common type for comparison. === checks equality of value and type, so different types always give false.
