<h1>Fizzbuzz</h1>

<p>In this problem you will be given an integer. For integer x you need to print from 1 to x using fizzbuzz format.

Fizzbuzz format dicatest that if the number is divisible by 3 you print the word "fizz".

If the number is divisible by 5 you print the word "buzz".

If the number is divisible by 15 you print the word "fizzbuzz".

If the number is not divisible by 5, or 3 you print the owrd "fizzbuzz".</p>

<h3>Example:</h3>

<p>the_integer = 16</p>
<p>
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
16
</p>

function fizzBuzz(integer){
  for(let i = 0; i<integer; i++){
    if(integer%5 != 0 && integer%15 != 0){
      console.log("fizzbuzz");
    }else if(integer%5 == 0){
      console.log("buzz");
    }else if(integer%3 == 0){
      console.log("fizz");
    }else if(integer%15 == 0){
      console.log("fizzbuzz");
    }else{
      console.log(integer);
