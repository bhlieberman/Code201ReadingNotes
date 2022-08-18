# Reading 03

## When to use an unordered list in HTML

Unordered lists are appropriate when there is no particular precedence or value assigned to the list items. This could be something like a grocery list, because it does not matter in which order you add the items, or in which order you buy them. (Unless you mapped out your grocery store and wanted to optimize your shopping experience, I guess.)

## Changing the bullet style of an unordered list

There is a `type` attribute on the `<ul>` HTML tag, but it is deprecated. The MDN docs specify that the CSS property `list-style-type` should be used instead.

## Using ordered vs. unordered lists

Ordered lists would be appropriate when there is precedence of some kind, be it chronological, preferential, etc. An example would be on a task list of some kind.

## Changing numbers of ordered lists

Unlike the same `type` tag on unordered lists, the `type` tag on ordered lists is not deprecated. It can be used to change the number type to Roman numerals, or letters, etc. But the CSS property `list-style-type` can also be used, as with unordered lists.

# Learn CSS

## The Box model




# Learn JS

## What data types can be stored in Arrays?

Anything. Arrays, Strings, Numbers, Booleans, Objects, and `null`. These data types can be mixed, because `Array` is a heterogenous container type.

## Is this nested Array valid?

Yes it is. Nested arrays are allowed in JS. You can access the array by using the index operators: like so
```js
let arr = [[1,2,3],[4,5,6]];
arr[1][0] // 4

```

## Five shorthand assignment operators

* `+=`: in-place addition
* `-=`: in-place subtraction
* `*=`: in-place multiplication
* `/=`: in-place division
* `=`: bind to a variable

## Evaluate the expression

```js
let a = 10;
let b = 'dog';
let c = false;

(a + c) + b // '10dog'
```

This expression evaluates to `10dog` because the JS interpreter interprets the first sub-expression `(10 + false)` as `(10 + 0)`, where 0 is the Boolean `false` coerced to a Number. It does this to prevent an error. Then, the result of `(10 + 0)` which is 10 is coerced to a String and concatenated to `dog`.

## Uses of conditionals

You could use a conditional to validate user input.

## Loops

Loops are useful when you need to operate on a container type, like an Array or Object. Loop constructs like `for` and `while` use a starting and a stopping condition and contain a body of logic that performs some operation on the data structure. When the stop condition is met, the loop ends and the execution of the rest of the program continues.
