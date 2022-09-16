# Reading 06

## JavaScript Object Basics

### What is an Object?

An Object is a collection of data. Effective use of Objects involves grouping this data together sensibly in order to describe real-world relationships. This could mean, for example, using an Object to store a person's biographical info. These data points are associated to named keys, i.e. `name` for their name, `phone` for their phone number, etc.

### Advantages of object literals

The names provided to information by an object literal can act as documentation or context for someone reading your code. A simpler data structure like an array has similar storage capabilities, but does not describe the data it contains.

### Using bracket notation with Objects

If an object literal is stored inside an array, or vice versa, bracket notation allows index-based access to this container and the data inside. This could happen if you had an object field that contained an array of a person's favorite foods, and you wanted to pick one.

### The `this` keyword

`this` is a reserved keyword in JavaScript that is self-referential. It refers to the object in which it is contained. In this example:

<code>
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}</code>

`this` applies to the object literal `dog`. `this.name` means "the field `name` on the object `dog`", which in this case will give the value Spot.

## The DOM

### What is the DOM?

DOM is an acronym for Document Object Model. The DOM is the application programming interface (API) of the web. It allows the programmer to make websites interactive by associating code-based actions with certain user-triggered events in the browser. JavaScript programmers write scripts that use the DOM's various interfaces and methods to change its appearance and structure. This is not a feature exclusive to JavaScript, as the DOM is an independent architecture, but JS is the primary language used for interacting with it.
