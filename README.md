# Trillo
Trillo project

[Live Preview](#) 🚀

*Taking notes while building the application from Jonas's tutorial => [Advanced CSS and SASS](https://udemy.com/course/advanced-css-and-sass).* ‼️

*The application might look different from the one from the tutorial. I am trying to change it as much as possible.* 👀

# FLEXBOX

To create a flex container we use the property `display: flex`.

The direct children of the flex container are called **flex items**.

Main axis represents `->`

Cross axis represents `↓`

**Container flex properties**:

* `flex-direction: row | row-reverse | column | column-reverse` 
* `flex: nowrap | wrap | wrap-reverse`
* `justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly`
* `align-items: stretch | flex-start | flex-end | center | baseline`
* `align-content: stretch | flex-start | flex-end | center | space-between | space-around`

**Item flex properties**:

* `align-self: auto | stretch | flex-start | flex-end | center | baseline`
* `order: 0 | <integer>`
* `flex-grow: 0 | <integer>`
* `flex-shrink: 0 | <integer>`
* `flex-basis: auto | <length>`
* Flex grow, shrink and basis can be combined into `0 1 auto`