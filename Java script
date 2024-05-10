// 1. write a function to sum two numbers
function sum(a,b){
  return a+b;
}
console.log(sum(3,8));

// 2. palindrome
 function palindrome (s){
   return s===s.split('').reverse().join('');
 }
 console.log(palindrome("slmmls"));
 
 //3. Reverse given String
 function Reverse(s){
   return s.split('').reverse().join('');
 }
 console.log(Reverse("dkllll"));
 
 //4. only Even
 function Even(arr){
   return arr.filter(num => num % 2 === 0);
 }
 console.log(Even([2,4,7,8,9,0,2]));
 
 // 5.deep clone
 function deepClone(obj) {
    return JSON.parse(JSON.stringify(obj));
}
const person = {
    a: 1,
    b: [2, 3,
    { c: 4 }],
    d:{ e: 5 }
};
console.log( deepClone(person));

// 6. Reverse without Reverse
   function reverseString(s) {
    let R = '';
    for (let i = s.length - 1; i >= 0; i--) {
       R+= s[i];
    }
    return R;
}
console.log( reverseString("mkooooo"));

//7. SumeOfarr
function SumOfArray(arr) {
    let sum = 0;
    for (let i = 0; i < arr.length; i++) {
        sum += arr[i];
    }
    return sum;
}
console.log(SumOfArray([1,2,3,4,5]));

// 8.factorial
function factorial(n) {
    if (n === 0 || n === 1) {
        return 1;
    }
    let result = 1;
       for (let i = 2; i <= n; i++) {
        result *= i;
    }
    return result;
}
console.log(factorial(5));

//9.Average
function average(arr) {
    if (arr.length === 0) {
        return 0;
    }
    let sum = 0;
       for (let i = 0; i < arr.length; i++) {
        sum += arr[i];
    }
       return sum / arr.length;
}
console.log(average([6,9,3,6,2]);
//10.
function findIndex(arr, target) {
      for (let i = 0; i < arr.length; i++) {
        if (arr[i] === target) {
                     return i;
        }
    }
       return -1;
}
console.log(findIndex([6,5,4,3,2],3));

//11.
function isInteger(num) {
    return Number.isInteger(num);
}
console.log(isInteger(9));
//12.
function ageInDays(ageInYears) {
    return ageInYears * 365;
}
console.log(ageInDays(25));
// A callback function: is a function that is passed as an argument to another function .
function hellooo(name, callback) {
    console.log("Hello, " + name );
       callback();
}
function hi() {
    console.log("Hi!");
}
hellooo("Omnia", hi);
