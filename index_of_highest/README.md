<h1>Index of an Array's Highest Value</h1>

<p>Given an array (or list) of integers, find and return the index of the highest value in the array.</p>

<p>Extra information about the array:</p>

<p>The array will always have at least one value, and will only ever contain integers.</p>

<h3>Example:</h3>

index_of_highest([-1,0,5,1,5,3,4,3]) => 2


function indexOfMax(arr) {
    var max = arr[0];
    var maxIndex = 0;

    for (var i = 1; i < arr.length; i++) {
        if (arr[i] > max) {
            maxIndex = i;
            max = arr[i];
        }
    }

    return maxIndex;
}
