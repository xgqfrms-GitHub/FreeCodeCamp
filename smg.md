#  why forbbiden I put new issues

## too hard for people to understand

## [https://www.freecodecamp.com/challenges/truncate-a-string](https://www.freecodecamp.com/challenges/truncate-a-string)
```js
function truncateString(str, num) {
		  // Clear out that junk in your trunk
		  var l = str.length;
		  var s = "";
		  if (l <= num) {
		  	s = str; 
		  } else if(num < 3){
		  	s = str.slice(0,num) + "...";
		  }else{
		  	s = str.slice(0,num-3) + "...";
		  }
		  return s;
		}
```
