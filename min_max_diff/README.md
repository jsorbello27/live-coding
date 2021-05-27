<h1>Min Max Difference</h1>

<p>In this problem you will be given an array/list of integers. You need to find the largest value and the smallest value in the array. Finally you need to return the difference (largest value - smallest value) of the two values.</p>

<h3>Example:</h3>

<p>the_array = [15, 22, 84, 14, 88, 23]</p>
<p>the_highest_value = 88</p>
<p>the_smallest_number = 14</p>
<p>the_difference = 74</p>

let highestNumber = 0;
let smallestNumber = 0;

function getHighest(arr){
  for(let i = 0;i<arr.length;i++){
    if(arr[i]>highestNumber){
    highestNumber = arr[i];
    }
  }
  return highestNumber
}

function getLowest(arr){
  for(let i = 0;i<arr.length;i++){
    if(arr[i]<smallestNumber){
    smallestNumber = arr[i];
    }
  }
  return smallestNumber
}

let solution = highestNumber - smallestNumber;
console.log(solution);


  

