# Solved-Tasks
```javascript

let basa = [];

let i;
for (i= 1; i<20; i+=2){
  basa.push (i);
}
console.log(basa);

let dama = [];
for (i= 1; i<11; i++){              
  dama.push(i % 2 === 0 ? -i: i);
}
console.log(dama);

numbers = [2, 13, 7, 6, 41, -7, 12, -4, 89, 5];
for (i = 0; i < 10; i++) {
  if (numbers[i] % 2 === 0) console.log(numbers[i])
  
for (i = 0; i > -10; i++) {
  if (numbers[i] < 0) console.log(numbers[i])
    }
  
  let nn = [];
  
  for (i = 0; i < 10; i++){
    if (numbers[i] > 10) nn.push(numbers[i])
  } 
  console.log(nn);
  console.log(nn.length);}

let numbers = [2, 13, 7, 6, 41, -7, 12, -4, 89, 5];


for (i = 0; i > -10; i++) {
  if (numbers[i] < 0) console.log(numbers[i])
    }

for (i = 0; i < numbers.length; i++) {
  if (numbers[i] < 0) numbers[i] = - numbers[i]
}

console.log(numbers)
{
    let arr = [];
    
    for (i = 20; i<= 30; i++) {
      arr.push(i)
    }
    console.log(arr);
    
    for (i = 5; i >= 1; i--) {
      arr.unshift(i)
    }
    console.log(arr);
}
;

for (i = 30; i < 25; i--) {
  arr.pop(i)
  console.log(i);
}
console.log(arr);

let str = '';
i = 0;
while (i < 27){
  str += 'Z'
  i++;
}
console.log(str);

i = 0;
while (i < 10 ) {
  console.log('Marie');
  i++;
}

i = -7;
while (i < 8) {
  console.log(i);
  i++;
}


for (i = 10; i >= 0; i--) {
  if (i === 0) i = 'start!';
  console.log(i);
}

for (let i = 10; i >= 0; i--) {
  if (i === 0) i = 'start!';
  console.log(i);
}

function numbersEvenOdd(a){
  if(a % 2 == 0) return ('Even')
  else return ('Odd')
    }
console.log(numbersEvenOdd(a));

let arr = [];
let arr2 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
function reverse (arr2) {
  for(i = arr2.length-1; i >= 0 ; i--) {
    arr.push(arr2[i]);
  }
  return arr;
}

console.log( reverse (arr2));

let x = 5;
let y = 10;
let arrXX =[];
let arrX =[0,1,2,3,4,5,6,7,8,9,10];
function newArray (x,y) {
    for (i = 0; i < arrX.length; i++) {
      if(arrX[i] <= y && arrX[i] >= x) arrXX.push(arrX[i]);
  }
  return arrXX;
}
console.log(newArray (x,y));

let arr1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
let a = 0;
function sum (arr1) {
  for(i=0; i < arr1.length; i++) {
    a = a + arr1[i];
  }
  return a;
}
console.log(sum (arr1));

a = 'Even';
d = 'PasV';

// function str(a){
//   for(value of a){
//     return (value);
//     break;
//   }
// } - this way also can be used, but it is longer

function str(a){
  return (a[0]);
}

console.log(str(a));
console.log(str(d));

let c = 25;
let d = 4;

function mult (c, d){
  return c * d;
}
console.log(mult(c, d));

function absValue(e){
  return Math.abs(e);
}
console.log(absValue(e));

{
    let arr = [21,22,23,24,25,26,27,28,29,30,31,32,33,34,35];
    let temp = [];
    
    for(i = 0; i < arr.length; i++) {
      temp.push(1.8*arr[i] +32);
    }
    console.log(temp);
   
}

{
    let x = 5;
    let y = 10;
    let arrXX =[];
    function newArrayX (x,y){
      if (x < y){
        for (i = x; i <= y; i++)
          arrXX.push(i);
      } else if (x > y){
        for (i = y; i <= x; i++)
          arrXX.push(i);
      } else if (x === y) arrXX.push(x);
      return arrXX;
    }
    console.log(newArrayX (x,y));
}

i = 0;
while (i < 15) {
 i+=2;
 console.log(i);
}
console.log('---------------');

let arr4 = ['apple', 'orange', 'grape', 'banana', 'mango', 'peach'];
let arr4X = [];

function countWords (arr) {
  let count = 0;
  for (let i = 0; i < arr.length; i++){
    if(arr[i].length === 5) count++;
  }
    return count;
}

console.log(countWords (arr4));

const arr = [1,5,7,3,2,8,0,9];
let temp;
for (let i = 0; i < arr.length-1; i++) {
  for(let j = i+1; j < arr.length; j++){
    if(arr[i]> arr[j]){
      temp = arr[i];
      arr[i]= arr[j];
      arr[j]= temp;
    }
  }
}
console.log("Hello, world!")

function sum (a, b){
    return a + b;
}
function mult(a, b){
    return a*b;
}
module.exports = {sum, mult};

const assert = require('assert');
const {sum, mult} = require('./index.js');

describe('function sum', () => {
    it('should function sum equals 6', () => {
        assert.equal(sum(2, 4), 6);
    })

    it('should function sum not equals 0', () => {
        assert.notEqual(sum(2, 4), 0);
    })
})


it('should mult equals 8', () => {
    assert.equal(mult(2, 4), 8)
})

function greet() {
let str = 'hello world!';
return str;
}

function createPhoneNumber(arr) {
  let a = '';
  let c = '';
  let d = '';
  for(i = 0; i < 3; i++) {
    a = a + arr[i];
  }
  for(i = 3; i < 6; i++) {
    c = c + arr[i];
  }
  for(i = 6; i < arr.length; i++) {
    d = d + arr[i];
  }
  return `(${a}) ${c}-${d}`
}

{
    var v1=50;v2=100,v3=150,v4=200,v5=2,v6=250
    function equal1(){
      var a=v1;
      var b=v1;
      return a+b;
    }
    //Please refer to the example above to complete the following functions
    function equal2(){
      var a=v3;   //set number value to a
      var b=v1;   //set number value to b
      return a-b;
    }
    function equal3(){
      var a=v1;   //set number value to a
      var b=v5;   //set number value to b
      return a*b;
    }
    function equal4(){
      var a=v4;   //set number value to a
      var b=v5;   //set number value to b
      return a/b;
    }
    function equal5(){
      var a=v6;   //set number value to a
      var b=v3;   //set number value to b
      return a%b;
    }
}

{
    let h, m, s;
    function past(h, m, s){
      h = h * 60 * 60 * 1000;
      m = m * 60 * 1000;
      s = s * 1000;
      return(h + m + s)
    }
}

let money = 10;
let candy = 1.42;
let chips = 2.4;
let soda = 1;
let change;
change = money - candy - chips - soda;
console.log(change);

{
    function getLength(arr){
      //return length of arr
      return arr.length;
    }
    function getFirst(arr){
      //return the first element of arr
      return arr[0];
    }
    function getLast(arr){
      //return the last element of arr
      return arr[arr.length-1];
    }
    function pushElement(arr){
      var el=1;
      //push el to arr
      arr.push(el);
      return arr;
    }
    function popElement(arr){
      //pop an element from arr
      arr.pop();
      return arr;
}

{
    // Codewars kata: Keep Hydrated!
    // Nathan loves cycling.
    // Because Nathan knows it is important to stay hydrated, 
    // he drinks 0.5 litres of water per hour of cycling.
    // You get given the time in hours and you need to return 
    // the number of litres Nathan will drink, rounded 
    // to the smallest value.
    
    function litres(time) {
      return Math.floor(time/2);
    }
}

{
    // Codewars Kata: Century From Year
    // The first century spans from the year 1 
    // up to and including the year 100, 
    // The second - from the year 101 up to 
    // and including the year 200, etc.
    
    function century(year) {
      return Math.ceil(year/100);
    }
}
{
    // Codewars Kata: Make a function that does arithmetic!
    // Given two numbers and an arithmetic operator
    // (the name of it, as a string), 
    // return the result of the two numbers 
    // having that operator used on them.
    // a and b will both be positive integers, 
    // and a will always be the first number 
    // in the operation, and b always the second.
    // The four operators are "add", "subtract", "divide", "multiply".
    
    function arithmetic(a, b, operator){
      //your code here!
      if(operator == 'add') return a + b;
      if(operator == 'subtract') return a -b ;
      if(operator == 'divide') return a / b;
      if(operator == 'multiply') return a * b ;
    }
}
{
    function arithmetic(a, b, operator){
      switch(operator) {
        case 'add':
          return a + b;
        case 'subtract':
          return a - b;
        case 'multiply':
          return a * b;
        case 'divide':
          return a / b;
      }
    }
}
{
    // Codewars Kata: Find the Slope
    // Given an array of 4 integers
    // [a,b,c,d] representing two points (a, b) 
    // and (c, d), return a string representation 
    // of the slope of the line joining these two points.
    // For an undefined slope (division by 0), 
    // return undefined . Note that the "undefined"
    // is case-sensitive.
    
    function slope(points)
    {
    let str = '';
    str = str + ((points[3] - points[1]) / (points[2] - points[0]));
       if((points[2] - points[0]) == 0) return str = 'undefined';
       else return str;
    }
}
{
    //Codewars Kata: Super Duper Easy
    //Make a function that returns the value 
    //multiplied by 50 and increased by 6. 
    //If the value entered is a string it should return "Error".
    
    
    function problem(x){
    if(typeof(x)=='string') return "Error";
    else if(typeof(x) == 'number') return (x * 50 + 6);
    }
}
{
    // Codewars Kata: Discover The Original Price
    //We need to write some code to return 
    //the original price of a product, the return type 
    //must be of type decimal and the number must be rounded to two decimal places.
    //We will be given the sale price (discounted price), 
    //and the sale percentage, our job is to figure out the original price.
    
    DiscoverOriginalPrice(75, 25) => 100.00M where 75 is the sale price (discounted price), 25 is the sale percentage and 100 is the original price
    function discoverOriginalPrice(discountedPrice, salePercentage){
      return Math.round(discountedPrice/(100-salePercentage) * 10000)/100
    }
}
{
    //Codewars Kata: Sum The Strings
    //Create a function that 
    //takes 2 positive integers in form 
    //of a string as an input, and outputs 
    //the sum (also as a string):
    
    function sumStr(a,b) {
      let sum = (a-0) + (b-0);
      return sum.toString();
    }
}
{
    //Codewars Kata: Convert a Boolean to a String
    //This katarepresent in code is the concept of true and false. 
    //A variable that can either be true or false 
    //is called a boolean variable. In this example, 
    //the input to boolean_to_string (represented by the variable b) is a boolean.
    
    function booleanToString(b){
      return b.toString();
    }
}
{
    //Codewars Kata: Convert a String to a Number!
    //We need a function that can transform a string 
    //into a number. What ways of achieving this do you know?
    
    let stringToNumber = function(str){
      return str-0;
    }
}
{
    //Codewars Kata: I love you, a little , a lot, passionately ... not at all
    //Who remembers back to their time in the schoolyard, 
    //when girls would take a flower and tear its petals, 
    //saying each of the following phrases each time a petal was torn:
    //I love you
    // a little
    // a lot
    // passionately
    // madly
    // not at all
    // When the last petal was torn there were 
    // cries of excitement, dreams, surging thoughts and emotions.
    // Your goal in this kata is to determine 
    // which phrase the girls would say for a flower 
    // of a given number of petals, where nb_petals > 0.
    
    function howMuchILoveYou(nbPetals) {
    let i, j;
        phrases = ['I love you', 'a little', 'a lot', 'passionately', 'madly', 'not at all'];
        
        for (i = 0; i < phrases.length; i++){
        if(nbPetals == i+1) return phrases[i];
        
         else for (j = nbPetals; j > 6;){
         nbPetals = nbPetals -6;
         j--;
         if(nbPetals<= 6) return phrases[nbPetals-1];
           }
        }
    }
}
{
    //Codewars Cata: Third Angle of a Triangle
    //You are given two angles (in degrees) of a triangle.
    // Write a function to return the 3rd.
    // Note: only positive integers will be tested.
    
    function otherAngle(a, b) {
      return 180-(a+b);
    }
}
{
    //Codewars Cata: Sum of angles
    //Find the total sum of angles in an n sided shape. N will be greater than 2.
    
    function angle(n) {
      let sum = (n-2) *180;
      return sum;
    }
}
{
    //Codewars Kata: Miles per gallon to kilometers per liter
    
    function converter (mpg) {
      let mile = 1.609344;
      let gallon = 4.54609188;
      let km = (mpg * mile)/gallon;
      return ( km.toFixed(2) )/1;
    }
}
{
    //Codewars Kata: Breaking chocolate problem
    
    // Your task is to split the chocolate bar of given 
    // dimension n x m into small squares. 
    // Each square is of size 1x1 and unbreakable. 
    // Implement a function that will return minimum number of breaks needed.
    // For example if you are given a chocolate bar of size 2 x 1 you 
    // can split it to single squares in just one break, 
    // but for size 3 x 1 you must do two breaks.
    // If input data is invalid you should return 0 
    // (as in no breaks are needed if we do not have any chocolate to split). 
    // Input will always be a non-negative integer.
    
    function breakChocolate(n,m) {
      let breaks =  n * m -1
      if(breaks < 0){
      return 0
      }
      else{
      return breaks
      }
    }
}
{
    //Codewars Kata: Convert boolean values to strings 'Yes' or 'No'.
    
    function boolToWord( bool ){
      switch(bool) {
        case true:
            return "Yes";
            break;
        case false:
            return "No";
            break;
        };
    };
}
{
    //Codewars Kata: Chuck Norris VII - True or False? (Beginner)
    //It's a well known fact that anything Chuck Norris wants, he gets.
    //As a result Chuck very rarely has to use the word false.
    //It is a less well known fact that if something is true, 
    //and Chuck doesn't want it to be, Chuck can scare the truth
    //with his massive biceps, and it automatically becomes false.
    //Your task is to be more like Chuck (ha! good luck!).
    //You must return false without ever actually using the word false...
    //Go show some truth who's boss!
    function ifChuckSaysSo(){
    return 2>3
    }
}//Codewars Kata: Formatting decimal places #0
 //Each number should be formatted that it is rounded 
 //to two decimal places. You don't need to check whether 
 //the input is a valid number because 
 //only valid numbers are used in the tests.
 
 function twoDecimalPlaces(n) {
   return (Math.round(n * 100))/100
 }
{
  //Codewars Kata: Type of sum
  //Return the type of the sum of the two arguments
  
  function typeOfSum(a, b) {
    return typeof(a + b);
  }   
}

}
```