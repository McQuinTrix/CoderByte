/*Have the function LongestWord(sen) take the sen parameter being passed and return the largest word in the string.
If there are two or more words that are the same length, return the first word from the string with that length.
Ignore punctuation and assume sen will not be empty.*/

function LongestWord(sen) { 

  // code goes here 
  var t =0;
  var arr = sen.split(" ");
  for(var a=0;a<arr.length;++a){
        arr[a] = arr[a].replace(/\W/g, '');
  		if(arr[a].length > arr[t].length){
        	t = a;
        }
  }
  return arr[t]; 
}
   
