<h1>Min Max Difference</h1>

<p>In this problem you will be given an array/list of integers. You need to find the largest value and the smallest value in the array. Finally you need to return the difference (largest value - smallest value) of the two values.</p>

<h3>Example:</h3>

<p>the_array = [15, 22, 84, 14, 88, 23]</p>
<p>the_highest_value = 88</p>
<p>the_smallest_number = 14</p>
<p>the_difference = 74</p>


function returnDifference(arr){
    let largestValue = arr[0];
    let smallestValue = arr[0];
    for(let i = 0;i<arr.length;i++){
        if(arr[i]>largestValue){
            largestValue = arr[i];
        }
        if(arr[i]<smallestValue){
            smallestValue = arr[i];
        }
        
    }
    let difference = largestValue - smallestValue
    return difference
}

returnDifference([5,4,9,2,1]);



  

