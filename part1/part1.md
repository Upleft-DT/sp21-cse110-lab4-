
## PART1a

1 It prints 'values added: 20'

2 It prints 'final result: 20'

3 It prints 'values added: 20'

4 Error because its not within the if(add) block

5 Error because result is a constant and it's being altered

6 Error because result is out of scope and result is being altered

## PART1b

1 It will print 3 because that's the final value i takes from the for loop

2 Print 150 because it does 300 * 0.5 in the final iteration of the for loop

3 Print 150 because it does rounded 150*100 then divides by 100

4 It will return an array containing 50, 100, 150 as it goes through the prices argument and multiplies by the discount

5 It will be an error because i only exists in the for loop

6 It will be an error because discountedPrice only exists in the for loop

7 It will output 150 because the console.log is within the scope of the let declaration and that's the final value it gets in the for loop

8 It should return an array with 50, 100, 150 in it

9 It will be an error because i only resides in the for loop scope

10 It will print 3 because thats the length of prices

11 It returns a const array containing 50, 100, 150. const only means the variable can't be reassigned. It can still be manipulated.

12 
1. student.name
2. student['Grad Year']
3. student.greeting();
4. student['Favorite Teacher']['name']
5. student['courseLoad'][0]

13
1. '32' because it turns 2 into '2'
2. 1 because the strings get turned into their numeric value
3. 3 because null becomes 0
4. 3null because null gets turned into its string representation
5. 4 because true becomes 1
6. 0 because both get turned into 0
7. 3undefined because undefined gets turned into a string
8. Nan because undefined becomes NaN not 0

14
1. true because '2' becomes 2
2. false because 2 is compared to 1 and it is not <
3. true '2' becomes 2
4. false because the strict equality marks false for different types
5. false because true becomes 1
6. True because it compares two booleans and any number non-zero is true
   
15 === checks equality without type conversion, == will do type conversion

17 The result will be a new array with 2,4,6 in it. First modifyArray takes in the 1,2,3 array and doSomething. Next in the for loop, doSomething with array[i] passed is called. The loop walks through array and passes their values to doSomething to be multiplied by 2 and stores them in a new array. That new array is returned.

19 The output is 1 4 3 2