# Reading 07

## Domain Modeling

Domain models act as a communication framework for project design and implementation. They help programmers develop an object-oriented model of real-world data. Additionally, they can be used to explain and delegate product requirements in such a way as to be usable by programmers and project managers alike.

## HTML Tables

### When not to use tables

Tables are for organizing structured, tabular data. Though they were once used as a layout tool on the early web, they interfere with proper accessbility for blind users or anyone using a screen reader. Tables also create "tag soup" in the HTML of a web page. They require heavily nested tag groups in order to achieve their structure and can be difficult to interpret.

### Three semantic elements of tables in HTML

* `<tr>`: This tag creates a table row: a horizontally-orientated grouping of data
* `<th>`: This tag creates a table header: the names for columnar data that appear at the top of the table
* `<td>`: This tag stands for table data and creates a single cell containing the text inside the tag

## Introducing constructors

A constructor is a root component of object-oriented programming in JavaScript. It associates data that is related in some real-world way to a named object. This object can then be built on a case-by-case basis using different data, eliminating the need for verbose and manual construction using object literals.

## `this` in constructors

When used in a constructor, the keyword `this` is associated to the instance of the object created when `new` is called. Like `this` in an object literal,it will only ever refer to the object itself and not to any other instance of that object.

## Inheritance and prototypes

Everyone owns a specific brand of car. But whether your car is electric or gas-powered, a sedan or an SUV, it has features that are common to all cars. Tires, two axles, an engine, a suspension, etc. If you wanted to diagnose an issue with your car, you don't necessarily have to consult documentation from the car manufacturer itself; a blowout is a blowout. A dead battery is a dead battery (okay, maybe not with electric cars, I know nothing about cars). This is analogous to prototypal inheritance in JavaScript. An object that is a certain brand of car can be associated with an object that describes behaviors, of cars, like `causeTraffic()` and `causePollution()`. These are not particular to any brand of car and will be stored in the separate object.
