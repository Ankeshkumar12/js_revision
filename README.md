# js_revision

# 📘 JavaScript Revision Notes

This file contains my **revision notes for core JavaScript concepts** that are essential for React.js and modern web development.

---

# 📚 Topics Revised

* Variables
* Functions
* Return Keyword
* Template Literals
* Loops
* Ternary Operators

---

# 1️⃣ Variables

Variables are used to **store data values** in JavaScript.

### Types of Variables

### `let`

Used when the value **can change**.

```javascript
let age = 20;
age = 21;
```

### `const`

Used when the value **should not change**.

```javascript
const name = "Ankesh";
```

### `var`

Older way of declaring variables (not recommended in modern JavaScript).

```javascript
var city = "Delhi";
```

---

# 2️⃣ Functions

Functions are blocks of code that **perform a specific task**.

### Example

```javascript
function greet(name) {
  console.log("Hello " + name);
}

greet("Ankesh");
```

### Arrow Function

```javascript
const greet = (name) => {
  console.log(`Hello ${name}`);
};
```

---

# 3️⃣ Return Keyword

The `return` keyword is used to **send a value back from a function**.

### Example

```javascript
function add(a, b) {
  return a + b;
}

let result = add(5, 3);
console.log(result);
```

Output:

```
8
```

---

# 4️⃣ Template Literals

Template literals allow us to **embed variables inside strings** using backticks.

### Example

```javascript
let name = "Ankesh";
let message = `Hello ${name}, welcome to JavaScript`;

console.log(message);
```

Output:

```
Hello Ankesh, welcome to JavaScript
```

---

# 5️⃣ Loops

Loops are used to **repeat a block of code multiple times**.

### For Loop

```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

### While Loop

```javascript
let i = 1;

while (i <= 5) {
  console.log(i);
  i++;
}
```

---

# 6️⃣ Ternary Operator

The ternary operator is a **short way to write an if-else condition**.

### Syntax

```javascript
condition ? trueValue : falseValue;
```

### Example

```javascript
let age = 18;

let message = age >= 18 ? "Adult" : "Minor";

console.log(message);
```

Output:

```
Adult
```

---

# 🧠 Purpose

These JavaScript concepts form the **foundation for learning React.js and modern frontend development**.
Regular revision helps strengthen problem-solving skills and improves code readability.
