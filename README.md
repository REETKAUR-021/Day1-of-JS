//JavaScript is a programming language used to create dynamic content for websites. It is a lightweight, cross-platform, and single-threaded programming language. JavaScript is an interpreted language that executes code line by line providing more flexibility.


//First Javascipt Program

console.log("Hello World!"); //Hello World!

//Variables 

// A variables is a container that stores data. In Javascript,variables are declared using the let , const , and var keywords.

//VAR keyword is used to declare a variable that can be changed(reassigning).var can be re-declared  . A global scope variable.
var num = 45;
console.log(num); //45

var num = 85;
console.log(num); //85  redeclared  and  reassigning the value.

//LET keyword  is used to declare a variable that can be changed(reassigning).let cannot be re-declared  . A block scope variable.

let number = 15; 
number = 25; //25 reassigning(updated) the value
console.log(number);

//CONST keyword is used to declare a variable that cannot be changed. const cannot be re-declared . a block scope variable.

const age = 21; //21 
console.log(age);

//DATATYPES : Primitive or Non Primitive data types

//primitive data type .

//1. Number
//A number value, e.g., 1, 2, 3, etc.
let a = 4;
console.log(a); //4

//2. String
//A sequence of characters, e.g., "hello", 'hello', etc.
let name = "Anmol"
console.log(name); //Anmol

//3. Boolean
//A true or false value.
let p = true;
console.log(p); //true

//4. Null
//A value that represents the absence of any object value.
let x = null;
console.log(x); //null

//5. Undefined
//A value that represents an uninitialized or non-existent variable.
let y;
console.log(y); //undefined

//6. Symbol
//A unique and immutable value, introduced in ECMAScript 2015.
let Sym = Symbol('My Symbol');
console.log(Sym); //symbol(My Symbol)

//7. BigInt
//A large integer value, introduced in ECMAScript 2020.
let bigNumber=1234567889584154121215n; //1234567889584154121215n
console.log(bigNumber);

//Non primitive data type
//Non-primitive types are objects and can store collections of data or more complex entities.

//1. Object
//A collection of key-value pairs, e.g., {name: 'John', age: 30}, etc.
let person = {
    name: 'John Doe',
    age: 30,
    occupation: 'Software Engineer'
  };
  console.log(person); //{ name: 'John Doe', age: 30, occupation: 'Software Engineer' }

  console.log(person.name); // John Doe for console single value
console.log(person.age); // 30

person.name = 'Jane Doe'; //update value
person.age = 31; 
console.log(person); //{ name: 'Jane Doe', age: 31, occupation: 'Software Engineer' }

person.country = 'USA'; //for added value
person.city = 'New York'; 
console.log(person); //{name: 'Jane Doe',age: 31,occupation: 'Software Engineer',country: 'USA',city: 'New York'}

delete person.age; // deleted value
console.log(person); //{name: 'Jane Doe',occupation: 'Software Engineer',country: 'USA',city: 'New York'}

//2. Array
//A collection of values, e.g., [1, 2, 3], ['a', 'b', 'c'], etc.
let colors = ["Red", "Green", "Blue"];
console.log(colors); //[ 'Red', 'Green', 'Blue' ]

console.log(colors[0]); // Red For single element access
console.log(colors[1]); // Green
console.log(colors[2]); // Blue

colors.push('Yellow'); //for added new element
console.log(colors); //[ 'Red', 'Green', 'Blue', 'Yellow' ]

colors[0] = 'Pink'; //for element update
console.log(colors); //[ 'Pink', 'Green', 'Blue', 'Yellow']

colors.splice(0, 1); //for delete element
console.log(colors); //[ 'Green', 'Blue', 'Yellow']

//3.Function
//Represents reusable blocks of code.
function Name() {
    console.log("hello i am function");
}
Name(); //hello i am function
   
//These data types are the foundation of JavaScript programming, and understanding them is essential for building robust and efficient applications.

