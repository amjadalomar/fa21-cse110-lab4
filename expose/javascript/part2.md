1. **3** will be outputted because i will have been incremented to be the length of the prices array before finishing in the for loop. It also outputs 3 and not a Reference Error because var variables can be accessed outside of their scope block
   
2. **150** will be outputted because discountedPrice will just overwrite itself every iteration until the last iteration where it will be 300 * .5 which is equal to 150.
   
3. **150** will be outputted because Math.round(discountedprice * 100) = 15000 and then when you divide that by 100 you just get 150 again. 
   
4. [**50**, **100**, **150**] will be outputted at the end of the function because it will add each discounted final price to the array and then return them once its all finished running. 
   
5. **Error**, because we are trying to access a let variable outside the scope of its block
   
6. **Error**, because we are trying to access a let variable outside the scope of its block
   
7. **150** will be outputted because Math.round(discountedprice * 100) = 15000 and then when you divide that by 100 you just get 150 again. 
   
8. [**50**, **100**, **150**] will be outputted at the end of the function because it will add each discounted final price to the array and then return them once its all finished running. 
   
9.  **Error**, becuase we are trying to access a let variable outside the scope of its block.
    
10. **3** will be printed because we are just accessing the value of the const value which was set to prices.length
    
11. [**50**, **100**, **150**] will be outputted at the end of the function because it will add each discounted final price to the array and then return them once its all finished running. 
    
12. a - student.name
    b - student['Grad Year']
    c - student.greeting()
    d - student['Favorite Teacher'].name
    e - student.courseload[0]

13. a - '32'
    b - 1
    c - 3
    d - '3null'
    e - 4
    f - 0
    g - '3undefined'
    h - NaN

14. a - true
    b - false
    c - true
    d - false
    e - true
    f - true

15. Both will check for equality of two given inputs however the difference comes with how strict the check of each variable is. For '==', the equality check will only compare the two variables and their values regardless of type, for example a string '12' and the int 12 would be true. For '===' however, it checks more strictly and will make sure that the type of the variables as well as their values are the same. Thus 12 and '12' would be false if compared with '==='.
    
16. in part2-question16.js file
    
17. The return will be the array **[2,4,6]**. I arrived at this answer by first checking what the passed in parameters were which in this case were an array holding [1,2,3] and a function 'doSomething'. Then i traced through the code given and into the for loop. Once at this for loop, i saw the line 'newArr.push(callback(array[i]));', so i looked at what the value for array[i] was going to be. Next, I checked what callback's value was and since it was the doSomething function, i calculated the return value for the function call. Lastly, I saw that we were pushing the returned value into a newArr. Then repeat for the other 2 values and return at the end of the function.
    
18. in part2-question18.js file
    
19. **1432**