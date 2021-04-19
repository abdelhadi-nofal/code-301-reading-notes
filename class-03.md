
## Javascript Templating Language and Engine— Mustache.js with Node and Express

![](https://miro.medium.com/max/700/1*YpdR22sjaflf8VWppz-y3g.png)

### Javascript Templating

Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.
The template engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client.


### Mustache

![](https://miro.medium.com/max/2400/1*P9q0tkeaRY2l1JOXaVKAig.png)

Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.
It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.
mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.

`Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn`

In the above, we see two braces around {{ name }}. This is Mustache syntax to show that it is a placeholder. When Mustache compiles this, it will look for the ‘name’ property in the object we pass in, and replace {{ name }} with the actual value, e,g, “Sherlynn”.
A confusion that I have initially was that Mustache is a templating engine. However, after some googling, I’ve come to learn that Mustache is NOT a templating engine. Mustache is a specification for a templating language. In general, we would write templates according to the Mustache specification, and it can then be compiled by a templating engine to be rendered to create an output.

![](https://miro.medium.com/max/700/1*LbqYj87xlazySm6wE0Q2lA.png)

### Mustache-Express


If you intend you use mustache with Node and Express, you can use mustache-express. Mustache Express lets you use Mustache and Express together easily.
To install:
With Yarn:

`$ yarn add mustache-express
`

or with NPM:

`$ npm install mustache --save
`

Configure mustache-express in your server.js/app.js/index.js file:

![](https://miro.medium.com/max/700/1*ES10lxr7tdRFVEKcRAgLEw.png)

Create a views folder and add some html view templates (e.g. hello.html):


![](https://miro.medium.com/max/494/1*zwYE8a5rvAVZcBl9v1oqfA.png)

![](https://miro.medium.com/max/700/1*FRcL9NQHI7Cvi2ELLmzJGQ.png)

***

## A Complete Guide to Flexbox


Chris Coyier on Apr 8, 2013 (Updated on Apr 7, 2021)

Our comprehensive guide to CSS flexbox layout. This complete guide explains everything about flexbox, focusing on all the different possible properties for the parent element (the flex container) and the child elements (the flex items). It also includes history, demos, patterns, and a browser support chart.

### ### Flexbox properties

display
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

flex-direction
the four possible values of flex-direction being shown: top to bottom, bottom to top, right to left, and left to right

This establishes the main-axis, thus defining the direction flex items are placed in the flex container. Flexbox is (aside from optional wrapping) a single-direction layout concept. Think of flex items as primarily laying out either in horizontal rows or vertical columns.

row (default): left to right in ltr; right to left in rtl
row-reverse: right to left in ltr; left to right in rtl
column: same as row but top to bottom
column-reverse: same as row-reverse but bottom to top

flex-wrap
two rows of boxes, the first wrapping down onto the second
By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.

flex-flow
This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.

justify-content
flex items within a flex container demonstrating the different spacing options

This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size. It also exerts some control over the alignment of items when they overflow the line.

align-items
demonstration of differnet alignment options, like all boxes stuck to the top of a flex parent, the bottom, stretched out, or along a baseline

This defines the default behavior for how flex items are laid out along the cross axis on the current line. Think of it as the justify-content version for the cross-axis (perpendicular to the main-axis).

align-content
examples of the align-content property where a group of items cluster at the top or bottom, or stretch out to fill the space, or have spacing.

This aligns a flex container’s lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.






