# Read: 14a - CSS Transforms, Transitions, and Animations

## CSS Transforms

- The CSS `transform` property allows us to size, position, and change elements
- The property has two settings:

1. two-dimensional
2. three dimensional

### Two dimensional

- Work on the x & y axes (horizontal and vertical axes)
- The different values of two dimensional:

1. `rotate` lets us rotate an element from 0-360 degrees. A positive value rotates the element clockwise and a negative value rotates the element counterclockwise.
2. `scale` lets us change the appeared size. Values between .99 and .01 make the size of the element appear smaller while values greater than, or equal to 1.01 make it appear bigger
3. `translate` pushes an element in different directions and it doesn't interrupt the flow of the document
4. `skew` distort the elements on either the horizontal axis, the vertical axis or on both. Skew is measured in units of degrees

- Using the `sclaeX` value scales the width of the element
- Using the `sclaeY` value scales the height of the element

### Three dimensional

- Determines the width and length of an element as well as the depth

## Transitions & Animations

- Using CSS3 allow us to alter the appearance, as well as the behavior of an element
- Transitions: There are a total of four transition-related properties:

1. `transition-property`
2. `transition-duration`
3. `transition-timing-function`
4. `transition-delay`