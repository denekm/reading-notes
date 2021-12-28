# Read 07: Object- Oriented Programming, HTML Tables

## Domain Modeling
https://github.com/codefellows/domain_modeling#domain-modeling

- object-oriented model has an entity that stores data in properties and it hides (encapsulates) the behavior of the methods.

## HTML Book: Chapter 6 - "Tables"

- We use tables to represent information in a grid format.

### The Basic Table Structure

`table`
  `<tr>`
    `<th></th>`
    `<td>1</td>`
  `<tr>`
`</table>`

- `<table>` use this element creates a table
- `<tr>` use this element to indicate the start of a row. tr means "table row"
- `<td>` use this to represent each cell of the table. td means "table data"
- `<th>` used to represent the heading. th means "table heading".

### Spanning Columns & Spanning rows

- we can use `<th>` and `<td>` to determine how many columns and rows a cell should span across or should span down

### Long Tables

If you are dealing with long tables we can split up the table into: head, body and footer:

- The heading of the table should be in `<thead>`
- The body should be inisde `<tbody>`
- The footer should be inside `<tfoot>`

## JS Book: Chapter 3 - "Functions, Methods and Objects

### Creating an Object: Construction Notation

Literal notation example:
`var hotel = {
  name: 'Hilton',
  rooms: 20,
  booked: 20
  checkAvaliability = function() {
    return this.rooms - this.booked;
  }`

Objecct Constructor Notation:
`var hotel = new Object();

hotel.name = 'Hilton',
hotel.rooms = 20,
hotel.booked = 20,
hotel.checkAvailability = function() {
  return this.rooms - this.booked
}`
