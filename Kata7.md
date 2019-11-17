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

* https://www.codewars.com/kata/testing-1-2-3/train/javascript
````js
var number=function(array){
  let arr1 = [];
  if (array.length === 0) return [];
  for(let i = 0; i < array.length; i++){
     arr1.push(`${i + 1}: ${array[i]}`);
   }
 return arr1;
}
````