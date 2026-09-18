# JavaScript Array Methods

A JavaScript practice project focused on understanding and applying different **array methods** to manipulate, search, filter, and evaluate data.

The project explores commonly used JavaScript array methods such as `some()`, `every()`, `find()`, `findIndex()`, and `filter()` through practical exercises.

## 🚀 Array Methods Covered

### `some()`

Checks whether **at least one** element in an array satisfies a condition.

```js
const hasAdult = people.some(
  (person) => new Date().getFullYear() - person.year >= 18
);
```

### `every()`

Checks whether **all** elements in an array satisfy a condition.

```js
const areAllAdults = people.every(
  (person) => new Date().getFullYear() - person.year >= 18
);
```

### `find()`

Returns the **first element** that satisfies a condition.

```js
const person = people.find(
  (person) => person.name === "John"
);
```

### `findIndex()`

Returns the **index of the first element** that satisfies a condition.

```js
const index = people.findIndex(
  (person) => person.name === "John"
);
```

### `filter()`

Creates a **new array containing all elements** that satisfy a condition.

```js
const adults = people.filter(
  (person) => new Date().getFullYear() - person.year >= 18
);
```

## 🛠️ Technologies Used

* JavaScript (ES6+)
* HTML5
* CSS3

## 📚 What I Practiced

Through these exercises, I practiced:

* Working with JavaScript arrays
* Using callback functions
* Understanding array iteration
* Working with objects inside arrays
* Conditional logic
* Using `some()` to check if at least one item matches
* Using `every()` to check if all items match
* Using `find()` to retrieve a specific item
* Using `findIndex()` to locate an item's position
* Using `filter()` to create a subset of data
* Working with dates using `Date`
* Writing cleaner and more concise JavaScript

## 🎯 Key Learning

These array methods are useful for working with collections of data without manually writing traditional `for` loops.

Understanding when to use each method is important:

| Method        | Purpose                                          |
| ------------- | ------------------------------------------------ |
| `some()`      | Checks if **at least one** item matches          |
| `every()`     | Checks if **all** items match                    |
| `find()`      | Returns the **first matching item**              |
| `findIndex()` | Returns the **index of the first matching item** |
| `filter()`    | Returns **all matching items**                   |

## 💻 Getting Started

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate into the project:

```bash
cd <project-folder>
```

Open the project in your browser or run it using a local development server such as VS Code Live Server.

## 👨‍💻 Author

**Oluwalayomi Lawore**

GitHub: **Layomi1**
