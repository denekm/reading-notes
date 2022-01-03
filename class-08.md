# Read: 08 - More CSS Layout

## Learn CSS - Layout

***![alt text](https://web.dev/learn/css/layout/)***

### The display property

- What does the display property do?
    1. It determines if the box it applies to is inline or block
        `.my-element{ display: block;}`
    2. It determines how the element's children will behave.
eg: when setting the `display` property to - `display: flex` makes the box block-level.
- Inline elements: are like words within a sentence

![alt text](https://web-dev.imgix.net/image/VbAJIREinuYvovrBzzvEyZOpw5w1/GezxDZXkJgkMevkKg39M.png?auto=format&w=741)

### Flexbox and Grid

- Flexbox and Grid are the two main layout mechanisims that make layout rules for different elements
- Flexbox example -
`.my-element { display: flex;}`
- ***Flexbox*** allows us to adjust the alignment, order as well as the justification on an item.
examples: `flex-grow:1`,
`flex-shrink:0`,
`flex-basis:auto;`

- Grid example -
`.myelement { display:grid; }`
- ***Grid*** controls the multi-axis layouts of the page while flexbox controls the vertical/horizontal space.
