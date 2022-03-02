# Read: Class 02 - State and Props

- [React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## Questions

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

* The 'render' happens first

2.What is the very first thing to happen in the lifecycle of React?

* The 'render' happens first
 Mounting is the first thing that happen in the lifecycle of React

3.Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

* Mounting, Updating, Unmounting, render, componentDidMount, componenetwillUnmount

4.What does componentDidMount do?

* componenetDidMount is used to load using network requests or in order to initialize the DOM

## Notes

- The three phases of the component lifecycle are mounting, updating, and unmounting
- During the ***mounting*** phase a particular of the component is created & it is placed to the DOM
- ***Updating*** - when a component is being updated it is rerendered
- ***Unmounting*** - componenetWillUnmount

## [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. What types of things can you pass in the props?

* Initial items, titles, and subtitles, 

2.What is the big difference between props and state?

* We pass props into a component while state is managed inside of that component. Props are managed outside of that component

3.When do we re-render our application?

* When the state is changed in our application

4.What are some examples of things that we could store in state?

* A form
