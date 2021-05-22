<h1>Index of an Array's Highest Value</h1>

<p>Given an array (or list) of integers, find and return the index of the highest value in the array.</p>

<p>Extra information about the array:</p>

<p>The array will always have at least one value, and will only ever contain integers.</p>

<h3>Example:</h3>

index_of_highest([-1,0,5,1,5,3,4,3]) => 2

let hightestArrValue = arr[i]
let highestValue = 0

function returnHighestValue(arr){
  for(let i = 0;i<arr.lenght; i++){
    if(highestArrValue> highestValue){
      let highestValue = i;
    }
   return highestArrValue;
