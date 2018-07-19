FizzBuzz

Objective

- To reinforce your understanding of flow control and comparison operators.



 Directions

- Write a program that console.logs the numbers 1 through 100.
- For multiples of 3, console.log('Fizz') instead of the number.
- For multiples of 5, console.log('Buzz') instead of the number.
- For numbers which are multiples of both 3 and 5, console.log('FizzBuzz') instead of the number.

Think thru and Write Out Solution

 write a loop that checks each number from 1-100 for multiples of 3 and 5

print the number to the console

assign the variable (n for number)

start with 1 and stop when it is < less than or  = equal to 100

keep adding 1 till we get to 100

    for(var n = 1; n<= 100; n++)

need to check for multiplies of 3 & 5 so need an if statement to test for a condition.  the condition is the n a multiple

need to use the % modulo because if it returns a remainder of 0 then it is divisible

try and divide by 3 and if the remainder is 0 then write fizz

    if (n % 3 === 0){
        console.log('fizz')
    }   

try and divide by 5 and if the remainder is 0 then write buzz

    else if (n % 5 === 0) {
        console.log('buzz')
    }    

try and divide by 3 and 5 and if the remainder is 0 for both then write fizz buzz

    else if (n % 3 === 0 && n % 5 === 0){
        console.log('fizzbuzz')
    }    

if it is none of the above write the number

    else {
        console.log(i);
    }

then need to put it in a function so that everything can pass thru it and we can call it or use it

    function fizzbuzz(){
        
    }

and hopefully this works! you need to make sure that the 3 and 5 is first becasue it will break once the first true statement is found

    function fizzbuzz(){
        
        for(var n = 1; n<= 100; n++)
            
          if(n % 3 === 0 && n % 5 === 0){
        console.log('fizzbuzz')
          }
            
          else if  (n % 3 === 0){
        console.log('fizz')
    }   
        
        else if (n % 5 === 0) {
        console.log('buzz')
    }    
        
       
        else {
        console.log(i);
    }
        
    }


