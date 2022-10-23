1. 3 will be printed, because i will be incremented by 1 after every iteration until it's not less than 3(the length of prices) anymore.
2. 150 will be printed, because discountedPrice holds the last value that it gets assigned to, which is prices[2]*(1 - 0.5) = 300 * 0.5 = 150.
3. 150 will be printed, because finalPrice holds the last value that it gets assigned to, which is Math.round(150 * 100)/100 = 150.
4. It'll return [50, 100, 150] which is an array of final prices calculated from the discount and the corresponding price in prices.
5. It'll cause an error because i is only visible in the for loop.
6. It'll cause an error because discountedPrice is only visible in the for loop.
7. 150 will be printed, because finalPrice is visible in the entire function, and it holds the last value that it gets assigned to, which is Math.round(150 * 100)/100 = 150.
8. It'll return [50, 100, 150] which is an array of final prices calculated from the discount and the corresponding price in prices. There won't be an error because discounted is visible in the entire function.
9. It'll cause an error because i is only visible in the for loop.
10. 3 will be printed because it's the length of the input array prices, which contains 3 elements.
11. It'll return [50, 100, 150] which is an array of discounted prices calculated from the discount and the corresponding price in prices. There won't be an error because discounted is visible in the entire function.
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. 32, because 2 is converted to a string
    B. 1, because 3 is converted to a number
    C. 3, because null is converted to number 0
    D. 3null, because null is converted to string
    E. 4, because true is converted to number 1
    F. 0, because false and null are both converted to number 0
    G. 3undefined, because undefined is converted to a string
    H. NaN, because '3' is converted to number 3 and undefined are converted to the number NaN, and 3 minus NaN is equal to NaN
14. A. true, because '2' becomes number 2 and 2 is greater than 1
    B. false, because the algorithm compares the first character first, and '2' is greater than '1'
    C. true, because '2' becomes number 2 and 2 is equal to 2
    D. false, because types are different
    E. false, because true is 1 and 1 is not equal to 2
    F. true, because Boolean(2) becomes true and true is equal to true
15. == checks equality with type conversion, whereas === checks equality without type conversion
16. (in part2-question16.js)
17. It will return [2, 4, 6]. First, define a new array for the results. Then we iterate through the input array, which is [1, 2, 3]. In each iteration, we call and pass the element in the array to doSomething, which returns the number multiplied by 2, and push the result to the newArr. So after 3 iterations, newArr will have 3 elements, each of which is the original number in [1, 2, 3] multiplied by 2.
18. (in part2-question18.js)
19. 1 
    4 
    3 
    2
