<h1>Reverse String</h1>

<p>In this problem you will be given a string. You will need to return the string in reverse.</p>

<h3>Example:</h3>

<p>the_string = "LaunchCode"</p>
<p>the_reversed_string = "edoChcnuaL"</p>

let reversedString = ""
function reverseString(string){
  for(let i = string.lenght - 1; i>=0; i--){
    reversedString += string[i]; 
    return reversedString;
  }
    
    
