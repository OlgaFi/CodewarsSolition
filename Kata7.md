* https://www.codewars.com/kata/find-the-middle-element/train/javascript
````js
var gimme = function (inp) {
 let arr = [];
 let num = 0;
 inp.forEach(el => arr.push(el))
 arr.sort((a,b)=> a-b);
 for (let i in arr){
   if(arr[1] === inp[i]) num = inp[i];
 }
 return inp.indexOf(num);
};
````