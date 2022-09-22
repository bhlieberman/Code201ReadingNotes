# React Forms

1. A controlled component is a React component in which the internal mutable state is controlled by the parent using `setState`. This can be a form that takes input, updating the state of the parent on each change.
2. I think this depends on what you are doing with the form. For the purposes of searching and filtering, the state could be updated on each keystroke. But if the form is for data submitted to another page, then it could be updated on submission only.
3. `event.target.value`

# The ternary operator

1. The ternary operator is a more expressive way to write simple conditional statements in three parts: a condition that evalutes to `true` or `false` and an expression that runs in either case. It is like a traditional `if/else` branch but can be more concise under certain circumstances.
2. ```
x === y ? console.log(true) : console.log(false)
```
