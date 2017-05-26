# JavaScript and DOM APIs

## Introduction

TBD

## Reading

1.  Eloquent JavaScript 2nd Edition [basic tutorial](http://eloquentjavascript.net/).

2.  Speaking JavaScript: An In-Depth [Guide](http://speakingjs.com/) for Programmers.

3.  [devdocs.io](http://devdocs.io/) to check Web platform documentation around JavaScript, frameworks, Browser APIs, etc.

## Extra Reading

*   Web Platform [Documentation](http://www.webplatform.org/) Project.

*   MDN JavaScript [Reference](https://developer.mozilla.org/en/JavaScript/Reference).

*   Understanding ECMAScript 6 [Guide](https://leanpub.com/understandinges6/read).

*   [ECMAScript® 2015 Language Specification](http://www.ecma-international.org/ecma-262/6.0/).

*   [JSONP](http://json-p.org/) - [CORS](http://www.html5rocks.com/en/tutorials/cors/).

*   [Using Chrome console to debug JavaScript](https://developer.chrome.com/devtools/docs/console).

## Practice

*Latest IE, Chrome and Firefox browser should be used. All exercises must be done with ECMAScript 6 syntax.*

1.  Creating our index page with some sections.

    *   Create a file called `index.html` with the correct doctype and some random content.

    *   Add a stylesheet to the HTML file and use it to center the texts of all `section` elements.

    *   Add a hidden `section` with `Hello World` inside of it.

    *   When the page finished loading the section must fade in.

2.  Adding some events

    *   Add a button below the `section` to your index page.

    *   Create a function that showcases an alert message when called.

    *   Attach a click event to the created button which calls the function previously created.


3.  Data fetching

    *   Create a function to get the response from [http://api.icndb.com/jokes/random](http://api.icndb.com/jokes/random).

    *   Replace the button's click event with this new function.

    *   Write the response inside the `section` element.

    *   Create a reusable function to perform AJAX calls. This function must accept a `config` object and return an ES6 Promise.

    *   If a server error occurs `section` content must turn red.

    *   **Hint:** Use the XMLHttpRequest to fetch data from the service.

4.  Data fetching with parameters

    *   Create a function to get the response from [https://api.github.com/search/repositories](https://api.github.com/search/repositories) with parameters `q = 'JavaScript'`.

    *   Showcase a list of repositories, provided by the service, in the right side of the screen.

    *   **Hint:** `ul` must be used to list the repositories.

    *   Add an input with `type="text"` to perform a search for any value.

5.  W3C

    *   Validate your page using W3C validator: [https://addons.mozilla.org/en-US/firefox/addon/web-developer/](https://addons.mozilla.org/en-US/firefox/addon/web-developer/)

6.  DOM manipulation

    *   Write a function that takes as input a matrix of data and outputs a DOM structure representing a table. Attach it to the body of a given page.

    *   **Hint:** use `document.createElement`, `document.createTextNode`, and `Node.appendChild` methods.

## Key Points

1, 3, 4, 6

→ [Bootcamp Overview](https://github.com/globant-ui-rosario/web-ui-bootcamp)
