# Read: Class 03 - Passing Functions as Props

## Lists and Keys

[Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?
. It returns an array
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
. We can use the map() function by including {} to get into JS. Example
`const number = [1,2,3,4,5];`
`const listNumbers = number.map((numbers) =>`
`<li>{numbers}</li>`
`);`
from [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
3. Each list item needs a unique ____.
. Key
4. What is the purpose of a key?
. The purpose of a key is to help React know when items have been changed, removed or added

## The Spread Operator

[The Spread Operator](https://reactjs.org/docs/lists-and-keys.html)

1. What is the spread operator?
. This operator helps us make our code be more readable by taking an array and having them as separate arguments
2. List 4 things that the spread operator can do.

- It can add items to the list 
- It combines objects
- It can combine/ concatenate arrays
- In React it can add to state

3. Give an example of using the spread operator to combine two arrays.
. `const myArray = [`🤪`,`🐻`,`🎌`]`
`const yourArray = [`🙂`,`🤗`,`🤩`]`
`const ourArray = [...myArray,...yourArray]`
`console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩` 
[Example from: Array concatenation](https://reactjs.org/docs/lists-and-keys.html)

4. Give an example of using the spread operator to add a new item to an array.
. `const fewFruit = ['🍏','🍊','🍌']`
`const fewMoreFruit = ['🍉', '🍍', ...fewFruit]`
`console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]`
[Example from: Adding an item](https://reactjs.org/docs/lists-and-keys.html)

5.Give an example of using the spread operator to combine two objects into one.
.
`[...["😋😛"]] // Array [ "😋😛" ]`
`[..."🙂🙃😉!"] // Array(9) [ "🙂", "🙃", "😉",`
 `"😊", "😇", "🥰", "😍", "🤩", "!" ]`

`const hello = {hello: "😋😛"}`
`const world = {world: "🙂🙃😉!"}`
`const helloWorld = {...hello,...world}`
`console.log(helloWorld) // Object { hello: "😋😛😜", world: "🙂🙃😉!"`
[Example from: Adding two objects](https://reactjs.org/docs/lists-and-keys.html)

## React - How to Pass Functions between Components - Episode 22
[Video](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?
. Create a function
2. In your own words, what does the increment function do?
. The increment function adds to the value that its given 
3. How can you pass a method from a parent component into a child component?
. `this.props`
4. How does the child component invoke a method that was passed to it from a parent component?
. `this.props.nameOfMethodFromParent()`