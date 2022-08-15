# How the Web works [MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

HTTP haiku:

*You send a request
The server sends a response
A webpage is here*

HTML documents are parsed top-to-bottom by the browser. Tags are read in this order, so any JS or CSS code that modifies unread tags will not work correctly. There are workarounds for avoiding this problem, like putting your `<script>` tags at the bottom of your HTML document.

The Web connects clients (your computer) with servers (someone else's computer, or a centralized system, that serves webpages and other content). Accessing a website consists of a making an *HTTP _request_*. The server sends a *_response_*.

But a webite's name/address that you type into the search bar does not neatly correspond to a name on the server. This is where the Domain Name System (DNS) comes in. It resolves the domain name of the requested website into an IP Address. This is a number that is recognized by the server and allows it to retrieve the webpage requested by the user.

# What your website will look like [MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

The first step when designing a website is planning. Even if it is your own website, you want a definite plan of its final state and not a jumble of ideas you iterate on while you write the code.

You want to know the who/what/why of your website. Who are your intended audience and users? What content will you be showing? Why is this content useful or important?

Then, you can start visualizing your site by sketching out its design or using some kind of graphical design software.

# JavaScript basic [MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

JavaScript is a programming language for making websites interactive.

JavaScript code can be executed in the browser by writing a `.js` script and refering to it in your HTML document, like so: `<script src="main.js"></script>`

JavaScript, like many other programming languages, uses *variables* to store data. These variables have *types*. JavaScript's basic types include:

* String
* Number
* Boolean
* Array
* Object
