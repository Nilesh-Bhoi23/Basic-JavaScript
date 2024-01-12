//this is printing method
/*this code is print to helloworld
using console.log*/
console.log("You Can Do It");

// Arithmatic operaters
// let a=5;
// let b=2;
// console.log(" a = ", a, " & b = ",b);
// console.log("a + b =",a + b); 
// console.log("a - b =",a - b); 
// console.log("a * b =",a * b); 
// console.log("a / b =",a / b); 
// //modulus operator
// console.log("a % b =",a % b); 
// //exponentiation operator
// console.log("a ** b =",a ** b);
// 5^2=25


//unary operator
// let a=5;
// let b=2;
// console.log(" a = ", a, " & b = ",b);

// console.log("a++ =",a++);

// console.log("a-- =",a--);

// console.log("++a =",++a);

// console.log("--a =",--a);

//Assignment operators
// let a = 5;
// let b = 2;

// a += 4; // a = a + 4
// console.log("a = ",a); //9

// a -= 4;// a = a - 4
// console.log("a = ",a); //5

// a *= 4 ;// a = a * 4
// console.log("a = ",a);//20

// a /= 4; // a = a / 4
// console.log("a = ",a);//1.25

// a %= 4; // a = a % 4
// console.log("a = ",a);//1

// a **= 4; // a = a ** 4
// console.log("a = ",a);//625


// comparison operators

// let a = 5;
// let b = 2;
// let c = 5;
// let d = "5";//string

// console.log("a == b", a == b);//False
// console.log("5 == 5", a == c);//True 
// console.log("5 != 5", a != c);//False 
// console.log("5 != 2", a != b);//True 
// console.log("a == d", a == d);//True
// console.log("a === d", a === d);//False 
// console.log("a !== d", a !== d);//True
// console.log("5 > 2", a > b);//True
// console.log("5 < 2", a < b);//False
// console.log("5 >= 2", a >= b);//True
// console.log("5 <= 2", a <= b);//False


// Logical operators

// let a= 6;
// let b= 5;

// let cond1 = a > b; //true
// let cond2 = a === 6; //true
// let cond3 = a === 5;
// console.log("cond1 && cond2=", cond1 && cond2);
// console.log("cond1 || cond2=", cond1 || cond3);
// console.log("cond1 && cond2=", a > b &&  a === 6);
// console.log("!(6<5)= ", !(a < b));//false but print true



// Conditional Statement
// if-statement

// let age=25;

// if(age >= 18) {
//     console.log("You can vote");
// }
// //output- you can vote

// let mode = "dark";
// let color;

// if(mode === "dark"){
//     color = "black";
// }

// if(mode === "light") {
//     color = "white";
// }

// console.log(color);
// // output-black

// if-else Statement
// eg-1
// let mode = "light";
// let color;

// if (mode === "dark") {
//     color = "black";
// }
// else {
//     color = "white";
// }
// console.log(color);

// eg-3

// let age=26;

//  if ( age >= 18) {
//     console.log("You can vote");
//  }
//  else {
//     console.log("Yov CANNOT vote");
//  }

// odd or even
// let num = 7;

// if (num%2 == 0) {
//     console.log(num,"is even");
// }
// else{
//     console.log(num," is odd");
// }


// else-if statement
// eg-

// let mode= "dark";
// let color;
//  if (mode === "dark") {
//     color = "black";
//  } else if (mode === "blue") {
//     color = "blue";
//  } else if (mode === "pink") {
//     color = "pink";
//  }else {
//     color = "white";
//  }

// console.log(color);

// // it is not useful
// if (mode === "dark") console.log(mode);

// // maximum use 
// if (mode === "dark") {
//     console.log(mode);
// }


// Ternary operator
// eg-1
// let age= 15;

// let res = age >=18 ? "adult" : "not adult";
// console.log(res);

// age >=18 ? console.log("adult") : console.log("not adult");

// age >=18 ? "adult" : "not adult";//simpler, compact if-else

// -------------------------------------

//alert box
//alert("how are you");//one time popup
// promt
// let fullName = prompt("hello");
// console.log(fullName);

// Practice Q-1 

// let num = prompt("enter a number");

// if(num % 5 === 0){
//     console.log(num,"is a multiple of 5");
// }
// else{
//     console.log(num,"is NOT a mutiple of 5");
// }



// Practice Q-2

// let score = prompt("enter your score(0-100");
// let grade;

// if(score >=90 && score<=100) {
//     grade = "A";
// }else if(score >=70 && score<=89){
//     grade = "B"
// }else if(score >=60 && score<=69){
//     grade = "C"
// }else if(score >=50 && score<=59){
//     grade = "D"
// }else if(score >=0 && score<=49){
//     grade = "F"
// }
// console.log("acording to your scores, your grade was=",grade);

// -------------------------------


// Loops in js
// loops are used to execute piece of code again & again

// for Loop
// print 1 to 5

// for (let i=1;i<=6;i++) {
//     console.log("NNN");//5 time  execute
// }
// console.log("Loop are ended");

//Calculate sum of 1 to 5

// let sum=0;
// for (let i = 1; i <= 5; i++) {
//     sum = sum + i;
//     console.log("sum=",sum);
// }
// console.log("final ans sum=",sum);
// console.log("loop has ended");

// let sum=0;
// let n=10;
// for (let i = 1; i <= n; i++) {
//     sum = sum + i;
//     console.log("i =",i);
//     console.log("sum =",sum);
// }
// console.log("final ans sum =",sum);
// console.log("loop has ended");


// Infinite Loop : A Loop that never ends 
// no use in code 

// While Loop
// Print 1 to 5

// let i=1;
// while (i <= 5) {
//     console.log("Nilesh");
//     i++;
// }

// do-while Loop
// it will be execute 1 time confirm

// let i =20;
// do {
//     console.log("Nilesh");
//     i++;
// }while (i <=10);

/* for loop
   while loop
   do-while loop
*/


// for-of Loop
// use for Arrays or Strings

// let str = "Nilesh Bhoi";
// let size = 0;
// for (let i of str) {//iterater -->characters
//     console.log("i =",i);
//     size++;
// }
// console.log("size =",size);

// for in loop

// let student = {
//     name: "nilesh kumar",
//     age : 21,
//     cgpa : 7.5,
//     isPass : true
// };

// for(let key in student) {
//     console.log("key =",key,"value=",student[key]);
// } 
//--------------------------------

// Practice Q.
// Qs-1) Print all even numbers from 0 to 100.
//1)
// let i = 2;
// for(i=2;i<=100;i=i+2) {
//     console.log("i =",i);
// }

//2)
// let i = 2;
// for(i=0;i<=100;i++) {
//     if (i % 2 === 0) {//even number
//         console.log("even =",i);
//     } else {
//         console.log("odd",i);
//     }
// }

//3)
// let i = 2;
// for(i=0;i<=100;i++) {
//     if (i % 2 !== 0) {//odd number
//         console.log("odd =",i);
//     }
// }

//------------------------------

// Practice Q. 2
// Qs2.
/* Creat a game where you start with any random game number .ask the user to keep gussing the game number until the user enters correct value */

// let gameNumber = 25;

// let userNum = prompt("guss the game number :");

// while(userNum != gameNumber) {
//     //game
//     userNum = prompt("you enterd wrong number, guess again :");
// }
// console.log("Congratulations, you entered the right number");

// //---------------------------

// String in js
// Strings is a sequence of Characters used to represent text 

// let str1 = "Nilesh bhoi";
// let str2 = "sushat shardul";
// // str1.length 
// // in console screen also work

// console.log("str length =",str1.length);

// //string indices
// //str1[0],str1[1],str1[2]

// console.log(str1[0]);//N


// Template Literals in js
// A way to have embedded in  strings 

//  `this is a template literal`

// String interpolation
// to create string by doing substitution of placeholders 

// `string text ${expression} string text`

// let obj = {
//     item : "pen",
//     price : 10
// };
// // T.L.

// let output = `the cost of ${obj.item}is ${obj.price} rupess`;
// console.log(output);
// // Normal..
// console.log("the cost of",obj.item,"is",obj.price,"rupess");

// // Template literals
// let specialString = `this is a template literal ${1+2+3}`;
// console.log(specialString);
// console.log(typeof specialString); 

// escape characters
// \n it is used to next line

// console.log("Nilesh\nbhoi");

// \t it is used for tab space
// it will be convert string in single word index..
// let str = "Nil\tDon";
// console.log(str.length);
// console.log("nil\tdon"); 

//-----------------------------

// Stirng Methods in js
// these are built-in function to manipulate a string 

// 1) str.toUpperCase()

// let str = "nileshbhoi";
// console.log(str.toUpperCase());//NILESHBHOI - it will be create a new string
// let newStr = str.toUpperCase();
// console.log("new string =",newStr);
// console.log("orignal string =",str);// nileshbhoi -it will be not change in orignal stritng

// string are immutable in javascript

// ----------------------------

// 2) str.toLowerCase

// let str = "NILESHBHOI";
// console.log(str.toLowerCase());//nileshbhoi
// // same as upper cass

// -----------------------------

// 3) str.trim( ) - removes whitespaces

// starting and ending space removes
// let str = "       nilesh bhoi   ";
// console.log(str.trim());

//--------------------------

// 4) str.slice(start,end?)-returns part of string

// let str = "bNileshb";
// console.log(str.slice(1,7));
// let str1= "1234546";
// console.log(str1.slice(1,6));

//---------------------------

// 5) str1.concat(str2)- joins str2 with str1

// let str1 = "my";
// let str2 = "name";
// let str3 = "is";
// let res = str1.concat(str2);
// console.log("res =",res);
// let res2 = str1 + str2;
// console.log("res2 =",res2);
// let res3 = str1 + str2 + str3;
// console.log(res3);


// 6) str..replace(searchVal.newVal)
// IT USED SO SEARCH NEW VALUE

// let str = "hello";
// console.log(str.replace("hello","yello"));
// // 7) str.replaceAll - it is used to rplace all simler char.
// console.log(str.replaceAll("l","p"));

// 8) str.charAt(idx) -  

// let str = "Ilovejavascript";
// str = str.replace("I","N");
// console.log(str);
// console.log(str.charAt(3));

//-----------------------------

// Let,s Practice
// Qs1 - Promt the user to enter their full name.generate a username for them based on the input.Start username with @.followed by their full name and ending with the fullname length.

// eg: user name ="nileshbhoi", username should be "@nileshbhoi10"

// let str1 = "@";
// let str2=prompt("enter your fullName");
// let res = str1 + str2 + str2.length;
// console.log(res);

// i solve s

// let fulName = prompt("enter your name");

// let userName = "@" + fulName + fulName.length;
// console.log(userName);

// free resources
// MDN.com

//------------------------------
//------------------------------

// Lecture 4:Arrays -
// Arrays in javascript
// Collection of items
// create Array -

// let heroes = ["ironman","hulk","thor","batman"];
// let marks = [89,56,48,90,78];
// console.log(marks,heroes);
// console.log(marks.length,heroes.length);

// Array indices
// arr[0],arr[1],arr[2]....
// array are muttable

// let heroes = ["ironman","hulk","thor","batman"];
// let marks = [89,56,48,90,78];
// console.log(marks[2]);// 48
// marks[2] = 70;
// console.log(marks[2]);// 70

//------------------------------

// Looping over in Array
// Print all element of an array
// iterable-loops

// let heroes = ["ironman","hulk","thor","batman","Nilesh"];
// // - using for loop
// for (i=0; i < heroes.length; i++) {
//    console.log(heroes[i]);
// } 

//----------------------------

// for of
// 1) 

// let heroes = ["ironman","hulk","thor","batman","Nilesh"];

// for(let hero of heroes) {
//    console.log(hero);
// }

//------------------------------

// 2)

// let cities = ["delhi","pune","mumbai","hyderabad","gurgaon"];

// for (let city of cities) {
//    console.log(city);
//    console.log(city.toUpperCase());
// }


// Let's Practice 
// // Qs.For a given array vith marks of students-->[85,97,44,37,76,60] Find the average marks of the entire class.

// let marks = [85,97,44,37,76,60];//array
// let sum = 0;
// for (let val of marks) {//loop
//    sum += val;
// }
// let avg = sum / marks.length;
// console.log(`avg marks of the class = ${avg}`);// string concept
// // Logical progaram

//------------------------------

/*Qs.For a given array with prices of 5 items -->[250,645,300,900,50]
all items have an offer of 10% OFF on them. chnage the array to store final price after applying offer.*/

// using for of loop
// let items = [250,645,300,900,50];
// let i = 0;
// for (let val of items) {
//    let offer = val / 10;
//    items[i] = items[i] - offer;
//    console.log(`value after offer = ${items[i]}`); // after offer apply
//    i++;
// } 

//----------------------------

// using for loop

// let items = [250,645,300,900,50];
// for (let i =0; i < items.length;i++) {
//    let offer = items[i] / 10;
//    items[i] -= offer;
// }
// console.log(items);

// //------------------------------

// Array Methods

// 1) push():add to end - it is used to add element in array 
// 2) pop():delete from end & return - it will be deleting item in ending.

// let fitem = ["potato","apple","tomato"];
// fitem.push("chips");
// fitem.push("c","t","d");
// console.log(fitem);

// 2)pop()
// 3) toString()
// let fitem = ["potato","apple","tomato"];
// let marks = [98,7,6,5,44,3,2];
// console.log(marks.toString()); 
// console.log(fitem.toString());// it used to print array in string.
// console.log(fitem);
// let delI = fitem.pop();
// console.log(fitem);
// console.log("deleted item =",delI);// tomato

//--------------------------------

// 3) Concat(): joins multiple array & returns result 

// let mh = ["thor","spiderman","ironman"];
// let dch = ["superman","batman"];
// let ih = ["krish","shaktiman","flyingjaat"];
// let heroes = mh.concat(dch,ih);
// console.log(heroes);

//------------------------------

// 4) unshift(): add to start - it work like push function.
// 5) shift(): delete from start & return.

// let marvelHeroes = ["thor","spiderman","ironman"];

// marvelHeroes.unshift("antman"); 
// let val = marvelHeroes.shift();
// console.log("deleted",val);

// 6)slice(): returns a piece of the array. - partucular part cut\
// slice(startidx,endidx)

// let marvelHeroes = ["thor","spiderman","ironman","antman","drstange"];

// console.log(marvelHeroes);
// console.log(marvelHeroes.slice(1,3));

// 7) splice():change orignal array (add,remove,replace)
// splice(stratidx,delCount,newEI1..)
// // #1
// let marvelHeroes = ["thor","spiderman","ironman","antman","drstange"];

// console.log(marvelHeroes);
// console.log(marvelHeroes.splice(2,0 ,101));

// #2

// let arr = [1,2,3,4,5,6,7];

// // //arr.splice(2,2,101,102);

// // //Ass Element
// arr.splice(2,0,101);

// // delete element

// // arr.splice(3,1);

// // replace element
// arr.splice(3,1,101);
// // Most useful merthod in array

//-------------------------------

// Let's Practice 
// Qs. Create an array to store companies-->
// --> "blooberg","microsoft","uber","google","IBM","Netflix"
// a.Remove the first company from the array
// b.Remove Uber & add ola in this place
// c.add amazon at the end

// let companies = ["blooberg","microsoft","uber","google","IBM","Netflix"];

// // companies.shift();
// companies.splice(2,1,"ola");
// companies.splice(6,0,"AMAZON");
//        //OR
// companies.push("amazon");
// I SOLVE 

//------------------------------

// Chapter 5 - Function & Methods

// function in JavaScript
//block of code that perform a specific task,can be invoked whenever needed
// create one time use multiple time.

// function myFunction() {
//    console.log("welcome");
//    console.log("javscript");
// }
// myFunction();

//----------------parameter

// function para(msg) {
//    //parameter--> input 
//    console.log(msg);
// }
// para("i love javascript");// argument

// multiple inputs ---
// Nan - not a number

// function mul(msg,num) {
//    //parameter--> \input 
//    console.log(msg,num);
// }
// mul("i love javascript",100);// argument

// sum 
// function with parameter not returning value
// function sum(x,y) {
//  console.log(x+y);  
// }
// sum(8347,7474);

// function sum(x,y) {
//    // x,y local variables -->scope
//    s = x + y;
//       return s;
//       // after return not run anything in block
// }
// let val = sum(89,7);
// console.log("value =",val);

// functions parameters are --> like local variables of function
// it has block scope (function block)

//--------------------------------


// Arrow function
// compact way of writing a function
// => arrow function 
// use for multiple work

// Modern js
//sum 

// const arrowsum = (a , b)=>{
//    console.log(a + b);
// };

//------------------------------

// const arrowmul = (a , b)=>{
//    console.log(a * b);
// };

// single line of A. fuc.-
// const printhello = () => console.log("hello");

//  const printhello = () => {
//    console.log("hello");
// }

//-----------------------------

// Let's Practice 
// Qs1) Create a function using the "function" keyword that takes a string as an argument & return the number of vowels in the string.

// Qs2) Create an arrow function to parform the same task.

// function countvowels(str) {
//    // "nileshbhoi" , count =4
//    let count = 0;
//    for (const char of str) {
//       if (char === "a" ||
//           char === "e" || 
//           char === "i" || 
//           char === "o" || 
//           char === "u") {
//          count++;
//       }

//    }
//    console.log(count);
// }

// using arrow function

// const countvowel = (str)=>{
//    let count = 0;
//    for (const char of str) {
//       if (char === "a" ||
//                 char === "e" || 
//                 char === "i" || 
//                 char === "o" || 
//                 char === "u") {
//                   count++;
//                 }
//    }
//    return count;
// };

//---------------------------------

// forEach loop in Arrays

// arr.forEach(callBackFunction)
//CallbackFunction : Here , it is a function to execute for each element in the array

// A callback is a function passed an an argument to another function.
// it's method -for array

// 1)
// let arr = [1,2,3,4,5];
// arr.forEach(function printval(val) {
//    console.log(val);
// });

// 2)
// it used to execute any work for array to forEach loop.

// let arr = ["puna","nashik","dilhi","mumbai"];
// arr.forEach(function printval(val, idx, arr) {
//    console.log(val.toUpperCase(),idx, arr);
// });

//------------------------------

// Qs.For a given array of number ,print the sequence of each value using the forEach loop.
// Ans
// it reaturn the squre of array

// let nums = [2,3,4,5,6];
// nums.forEach((num) => {
//    console.log(num * num);//num**2
// }); 

//--------------------------

// let nums = [2,3,4,5,6];

// let calcSquare = (num) => {
//    console.log(num * num);//num**2
// }; 
// // Function pass using forEach loop.
// nums.forEach(calcSquare);


//===============================


// some more array methods
// Map - method
// it will be return new array 

// Create a new array with the result of some opration. the value its callback returns are used to from new array
// arr.map(callbackFnx(value ,index, array))

// let nums = [67,52,39];

// let newArr = nums.map((val) => {
//   return val;
// });
// console.log(newArr);

//---------------------------

// let nums = [67,52,39];

// let newArr = nums.map((val) => {
//   return val * val;
// });
// console.log(newArr);
// it will perform task and return new array. 

//------------------------------

// Filter method

// Create a new array of element that give true for a condition/filer.
// Eg- all elements

// let arr = [1,2,3,4,5,6,7,8,9,10];

// let evenArr = arr.filter((val)=>{
//    return val % 2 === 0;
// });

// console.log(evenArr);

//--------------------------

// let arr = [1,2,3,4,5,6,7,8,9,10];

// let oddArr = arr.filter((val)=>{
//    return val % 2 !== 0; // condition wise work like loop 
// });

// console.log(oddArr);

//============================

// Reduce Method
// Perfoms some opration & reduce the array to a single value. it returns that single value.
// calculating all numbers

// let arr = [1,2,3,4,5,6];

// const output = arr.reduce((prev , curr) =>{
//    return prev + curr;
// });

// console.log(output); 

//-------------------------------

// largest number in arr findout using this method

// let arr = [4,5,1];

// const output = arr.reduce((prev , curr) =>{
//    return prev > curr ? prev : curr;// if you want smallest number (>) = < cange this condition; 
// });//5

// console.log(output); 

//=============================

// Qs. 1) We are given array of students.Filter out of the marks of the marks of students that scored 90+.

// let marks = [90,78,91,75,98,55,95];

// let score = marks.filter((val)=> {
//    return val >= 90;
// });

// console.log(score);

//----------------------------

// Qs.2) Take a number n as input from user . Create an array of numbers from 1 to n. use the reduce method to calculate sum of all numbers in the array. use the reduce method to calculate product of all numbers in the array.
//================

// let n = prompt("enter a number :");

// let arr = [];

// for(let i=1; i<=n; i++) {
//    arr[i-1] = i; // 1(0), 2(1), 3(2), 4(3) 
// }

// console.log(arr); 

// let sum = arr.reduce((res , curr) => {
//    return res + curr;
// });

// console.log("sum",sum);

// let factorial = arr.reduce((res , curr) => {
//    return res  * curr;
// });
// console.log("factorial",factorial);




















