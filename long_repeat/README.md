<h1>Length of Longest Repeating Substring</h1>

<p>In this problem you are given a string of alphabetic characters. You need to find the length of the longest substring of repeating characters.</p>

<h3>Examples:</h3>

<p>longRepeat("aaa") => 3</p>
<p>longRepeat("a") => 1</p>
<p>longRepeat("bdsagbgagggaaatttyyyyau") => 4</p>
<p>longRepeat("abcdefghijklmnopqrstuvwxyz") => 1</p>
<p>longRepeat("") => 0</p>

function longRepeat(line){
    longCount = 0;
    currChar = "";
    currCount = 0
 
    
    for(let i = 0;i<line.length;i++){
        if (line[i] === currChar){
            currCount ++;
        }else{
            currChar = line[i];
            currCount = 1;
        }
        if(currCount>longCount){
            longCount = currCount;
        }
    }
    return longCount;
}


longRepeat("aaaabnmmmmmmmm")
