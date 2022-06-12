## requirement 
    
- Create a new main.js file and write a function that does the following: determine whether a string is a palindrome string. (Palindrome, a string read from the beginning as well as from the end. For example, abcba is a palindrome string.)

```
function palindrome(message){
  // wirte your code here
  var arr=message.split('');
  var len=arr.length
  for(let i=0;i<Math.floor(len/2);i++)
  {
    if(arr[i]!==arr[len-1-i])
      return false;
  }
  return true;
}
console.log(palindrome('hello')); // should return false
console.log(palindrome('abcba')); // should return true
```
