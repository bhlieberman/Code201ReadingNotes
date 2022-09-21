# React docs

1. It returns a new array containing the result of the callback function passed to it.
2. JSX only expects JS expressions passed in curly braces. In order to simply inspect a value, you could use `.forEach` like so:
```{arr.forEach(itm => console.log(itm))}```
but in order to operate on the item you need to use `.map`
3. Key
4. Keys help React know why elements have changed and must be re-rendered.

# The spread operator

1. The spread operator is JS syntax for destructuring and constructing new arrays. It can be use to copy all or some elements of one array or iterable into another.
2. The spread operator can:
  * Copy an array
  * Concatenate two arrays
  * Adding state to React
  * Passing arguments into functions that expect non-iterables
3. 
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
const arr3 = [...arr1, ...arr2];
```
4. 
```
const arr1 = [4, 5, 6];
const arr2 = [1, 2, 3, ...arr1];
```
5. 
```
const obj1 = {name: "Ben, hobbies: "Reading"};
const obj2 = {...obj1, job: "Programmer"};
```

# Videos

1. They define an `increment` function in the parent component.
2. It updates the state of the child's component's counter.
3. Using props and defining a method on the parent.
4. `this.props.method()`
