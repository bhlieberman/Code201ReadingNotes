# Reading 02

# Introduction to HTML

## Why use semantic elements?

Semantic elements like `<p>` and `<section>` are more descriptive. They act as documentation for someone reviewing your HTML. Additionally, accessibility tools like screen readers benefit from the more specific naming of tags.

## How many heading levels are there?

There are six heading tags: `<h1> <h2> <h3> <h4> <h5> <h6>`.

## What are the `<sub>` and `<sup>` tags for?

`<sub>` is the HTML tag for `subscript`. This might be used to represent formulas on a website about chemistry. `<sup>` is the corresponding `superscript`. It could likewise be used in a scientific context, e.g. the representation of mathematical formulas.

## What attribute does the `<abbr>` tag require?

The reader needs to know what the abbreviation in `<abbr>` expands to. This can be provided outside of the tag in plain text or as an attribute `title`. If the attribute is used, the browser will display a tooltip with the expanded acronym when the text is scrolled over.

# Learn CSS

## How can we apply CSS to our HTML?

You can write CSS in a `.css` file and point the browser to its location in the filesystem by using the `<link rel="stylesheet" href="styles.css">` tag. Alternatively, you can write inline CSS by applying the `style` attribute directly to the chosen tag. Or, you can write CSS as it would appear in a `.css` file directly in your HTML by using the `<style>` attribute in the `<head>` of your document.

## Why are inline styles bad?

Separation of concerns: code and content are different. In an HTML document, excessive usage of CSS is both noise for anyone reading the source and an additional maintenance burden for whoever is working with the code.

## About this CSS block:

<code>h2 {
      color: black;
	  padding: 5px;
 }</code>

1. The selector is `h2`.
2. `color` and `padding` are the CSS properties in this code block.
3. Both components are declarations when taken together as a key-value pairing. E.G. `color: black` is a CSS declaration.

# Learn JS

## What is the data type of `'this'`

A sequence of text enclosed in single- or double quotes, like the titular 'this', is a String. This is a fundamental data type in JavaScript.

## Four JS operators

* `=`: assignment
* `+`: addition
* `||`: logical OR
* `&&`: logical AND

## Real world problem

If I were a teacher who wanted to make my gradebook digital, I could use a JS function to adjust students' grades as necessary. For example, I could select all the students who were absent on a given day and decrement their grades by a certain amount.

## Making decisions in code

1. An `if` statement checks a condition and if it evalues to `true`, then the code block will execute.
2. An `else if` statement/block will be executed if the preceding `if` statement evaluates to `false`.
3. `>: greater than; <: less than; ===: strict equality`
