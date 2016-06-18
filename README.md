# proj_euler_js
Project Euler problems using JavaScript

........................................................................
/* 
Problem 1

If we list all the natural numbers below 10 that 
are multiples of 3 or 5, we get 3, 5, 6 and 9. The 
sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000. 
*/

sum = 0;

for(i = 0; i < 1000; i ++){
    if(i % 3 == 0){
        sum += i;
    }else if(i % 5 == 0){
        sum += i;
    }
}

console.log(sum);
........................................................................

/* 
Problem 2

Each new term in the Fibonacci sequence is generated 
by adding the previous two terms. By starting with 1 
and 2, the first 10 terms will be:

1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

By considering the terms in the Fibonacci sequence whose 
values do not exceed four million, find the sum of the 
even-valued terms.
*/

sum = 0;
x = 1;
y = 2;

while(y < 4000000){
    test = x + y;
    if(test % 2 == 0){
        sum += test;
    }
    x += (y - x);
    y = sum;
}

console.log(sum);
........................................................................
/*
Problem 3

The prime factors of 13195 are 5, 7, 13 and 29.

What is the largest prime factor of 
the number 600851475143 ?
*/

... not finished yet