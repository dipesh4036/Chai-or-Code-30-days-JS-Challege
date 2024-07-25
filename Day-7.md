# Day-6 : Object:

## Activity : 1 Object Creacion and Access

Task : 1 Create an object representing a book properties like title and author and year and log the object to the console.

Task : 2 Access and log the title and author properties of the book object.

```javascript
// task : 1 and 2

// Task 1
const book = {
  title: "the somthing",
  author: "XYZ",
  year: 2009,
};

console.log(book);
// Task 2

console.log(book.title);
console.log(book.author);
```

## Activity : 2 Object Methods

Task : 3 Add a method to the book object that return that returns a string with the book's title and author and log the result of calling this method.

Task : 4 Add a method to the book object that takes a parameter(year) and updates the book's year property then log the updated object.

```javascript
// task : 3
const book = {
  title: "the somthing",
  author: "XYZ",
  year: 2009,
  method: () => {
    return `this is book title: ${this.title} and author name: ${this.author}`;
  },
};

console.log(book.method());
// Task : 4
const book = {
  title: "The Something",
  author: "XYZ",
  year: 2009,
  updateYear: function (newYear) {
    this.year = newYear;
    return this;
  },
};

console.log(book.updateYear(2010));
```

## Activity 3 : Nested Objects

Task : 5 Create a nested object representing a library with properties like name and books(an array of book objects), and log te libaray object to the console.

Task : 6 Access and log the name of the libaby and the titles of the books in the library.

```javascript
// task : 5
// Task 5
const library = {
  name: "Something Library",
  books: [
    {
      title: "Hello",
      author: "Author1",
      year: 2000,
    },
    {
      title: "World",
      author: "Author2",
      year: 2010,
    },
  ],
};

console.log(library); // Logs the entire library object

// Task : 6
console.log(library.name);

for (let i = 0; i < library.books.length; i++) {
  console.log(library.books[i].title);
}
```

## Activity : 4 the THIS keyword:

Task : 7 Add a method to the book object that uses the **this** keyword to return a string with the book's title and year , and log the result of calling this method.

```javascript
// Task : 7
const book = {
  title: "the somthing",
  author: "XYZ",
  year: 2009,
  method: function () {
    return `this is book title: ${this.title} and author name: ${this.author}`;
  },
};

console.log(book.method());
```

## Activity : 5 Object Iteration:

Task : 8 Use a For...in loop to iterate over the properties of of the book object and each property and its values.

Task : 9 Use Object.key and Object.values methods tolog all the keys and values of the book object.

```javascript
// Task : 8
const book = {
  title: "The Something",
  author: "XYZ",
  year: 2009,
};
for (let prop in book) {
  console.log(`${prop}: ${book[prop]}`);
}


// Task : 9
const keys = Object.keys(book);
const values = Object.values(book);

console.log("Keys:", keys);
console.log("Values:", values);

```

## Achievement:

• Create and manipulate object with properties and mehtods.

• Understand and use the this keyword in object methods.

• Work with nested objects and arrays of objects.

• Iterate over an object's properties using loopd and bulid-in methods.
