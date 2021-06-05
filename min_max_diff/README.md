<h1>Min Max Difference</h1>

<p>In this problem you will be given an array/list of integers. You need to find the largest value and the smallest value in the array. Finally you need to return the difference (largest value - smallest value) of the two values.</p>

<h3>Example:</h3>

<p>the_array = [15, 22, 84, 14, 88, 23]</p>
<p>the_highest_value = 88</p>
<p>the_smallest_number = 14</p>
<p>the_difference = 74</p>

let theArray = [1,2,3,4,5,6]
let highestValue = theArray[0]
let lowestValue = theArray[0]

for(let i = 0;i<theArray.length;i++){
    if(theArray[i]> highestValue){
        highestValue = theArray[i];
    }
    if(theArray[i]<lowestValue){
            lowestValue = theArray[i];
    }
}
console.log(highestValue);
console.log(lowestValue);

let theDifference = highestValue - lowestValue
console.log(theDifference)



  

