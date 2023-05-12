  <h1>Introduction</h1>

  <p>JavaScript is a dynamic programming language that is widely used in web development. It can be used both on the client-side and server-side, and is known for its flexibility and ease of use.</p>

  <h2>Data Types</h2>

  <p>JavaScript has several data types, including numbers, strings, booleans, objects, and arrays. Here are some examples:</p>

  <pre>
let number = 42;
let string = "Hello, World!";
let boolean = true;
let object = { name: "John", age: 30 };
let array = [1, 2, 3, 4, 5];
  </pre>

  <h2>Variables</h2>

  <p>Variables are used to store data in JavaScript. They can be declared using the <code>var</code>, <code>let</code>, or <code>const</code> keywords. Here are some examples:</p>

  <pre>
var x = 5;
let y = 10;
const z = 15;
  </pre>

  <p>The <code>var</code> keyword is used to declare a variable that can be reassigned. The <code>let</code> keyword is used to declare a variable that can be reassigned, and the <code>const</code> keyword is used to declare a variable that cannot be reassigned.</p>

  <h2>Functions</h2>

  <p>Functions are used to group a set of statements together to perform a specific task. They can be defined using the <code>function</code> keyword. Here are some examples:</p>

  <pre>
function sayHello(name) {
  console.log("Hello, " + name + "!");
}

sayHello("John"); // Output: Hello, John!
  </pre>

  <h2>Control Flow</h2>

  <p>Control flow is used to determine the order in which statements are executed in a program. JavaScript has several control flow statements, including <code>if</code>, <code>else if</code>, <code>else</code>, <code>for</code>, <code>while</code>, and <code>switch</code>. Here are some examples:</p>

  <pre>
if (x > 10) {
  console.log("x is greater than 10");
} else if (x < 10) {
  console.log("x is less than 10");
} else {
  console.log("x is equal to 10");
}

for (let i = 0; i < 5; i++) {
  console.log(i);
}

while (x < 10) {
  console.log(x);
  x++;
}

switch (x) {
  case 1:
    console.log("x is 1");
    break;
  case 2:
    console.log("x is 2");
    break;
  default:
    console.log("x is not 1 or 2");
}
  </pre>

  <h2>Objects and Arrays</h2>

  <p>Objects and arrays are used to store and
manipulate data in JavaScript. Objects are collections of key-value pairs, while arrays are ordered collections of values. Here are some examples:</p>

  <pre>
let person = {
  name: "John",
  age: 30,
  address: {
    street: "123 Main St",
    city: "Anytown",
    state: "CA",
    zip: "12345"
  }
};

let numbers = [1, 2, 3, 4, 5];
  </pre>
  <p>You can access and modify values in objects and arrays using dot notation and bracket notation. Here are some examples:</p>
  <pre>
console.log(person.name); // Output: John
console.log(numbers[0]); // Output: 1

person.age = 40;
numbers.push(6);

console.log(person.age); // Output: 40
console.log(numbers); // Output: [1, 2, 3, 4, 5, 6]
  </pre>
  <h2>Classes</h2>
  <p>Classes are used to create objects with similar properties and methods. They were introduced in ECMAScript 2015. Here is an example:</p>
  <pre>
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  sayHello() {
    console.log("Hello, my name is " + this.name + " and I am " + this.age + " years old.");
  }
}

let john = new Person("John", 30);
john.sayHello(); // Output: Hello, my name is John and I am 30 years old.
  </pre>
  <h2>Conclusion</h2>
  <p>JavaScript is a powerful and versatile programming language with many useful features and capabilities. By understanding the core concepts outlined in this document, we will be well on your way to becoming a proficient JavaScript developer.</p>
