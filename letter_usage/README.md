<h1>Letter Usage</h1>

<p>In this problem you will be given a string. Your string is a representation of a phrase. It can contain words, and spaces. You need to return a hashmap/dictionary that contains the number each character occurs in the original string.</p>

<h3>Example:</h3>

<p>the_string = "My name is Fred"</p>
<p>
answer = {
    "M": 1,
    "y": 1,
    " ": 3,
    "n": 1,
    "a": 1,
    "m": 1,
    "e": 2,
    "i": 1,
    "s": 1,
    "F": 1,
    "r": 1,
    "d": 1
}
</p>


the_string = "My name is Fred"
lettersMap = {};

// answer = { "M": 1, "y": 1, " ": 3, "n": 1, "a": 1, "m": 1, "e": 2, "i": 1, "s": 1, "F": 1, "r": 1, "d": 1 }

for(let i = 0;i<the_string.length; i++){
    if(lettersMap[the_string] === undefined){
        lettersMap[the_string[i]] = 1;
    }else{
        total = lettersMap[the_string[i]];
        lettersMap[the_string[i]] = total + 1;
    }
}
console.log(lettersMap);
