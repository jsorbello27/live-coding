<h1>How Many Words?</h1>

<p>In this problem you will be given a string. Your string is a representation of a phrase. It can contain words, and spaces. You need to return the number of words in the phrase.</p>

<h3>Example:</h3>

<p>the_string = "The dog jumps over the cat."</p>
<p>num_of_words = 6</p>

let counter = 0;
function numberOfWords(string){
    for(let i = 0;i<string.length;i++){
        if(string[i] == " "){
            counter++ 
        }
    }   
    return counter+1
}

numberOfWords("The Cow is Mooing");
 or
 
 function returnWords(string){
let  stringArr = string.split(" ");
 return stringArr.length + 1;

