# Questions From Companies

## Company A

- Do you use a Mac?
- What are you doing now?
- Why are you looking for work?
- Why Us?
- 3 things you would improve about yourself? 
  - Interviewer starts with an example about himself. Goes with a workaholic.
- How do you handle conflict in the workplace?
- What's your greatest accomplishment in the business world?
- CI/CD, are you comfortable working with that?
- How are you with mentoring, growing, less-experienced talent?
- In the 6 minutes we've been talking 8 new languages and 17 new frameworks have been created. How do you keep up with languages and technology updates?
- How many projects have you started from scratch and helped design and architect?
- Are you familiar with GraphQL?
- Are you familiar with REST?
- How do you add things to a redux store, how do you get things out of the redux store?
  - Use REDUCERS to add to the store, use SELECTORS to get from the store.
- Are you familiar with Higher Order Components? 
  - He probes for the term WrappedComponent referencing the child component.
- What's the issue with testing the Wrapped Component that is wrapped with 40 Higher Order Components? 
  - You have to mock the higher order components because you're not testing those, you're testing the wrapped components.
- Have you worked on Internationalization?
- Have you done any SSR (server-side rendering) work with React? I just use Gatsby / Next
- Name 4 principles of REST
- How do you handle errors in React? 
- Answer from: 1) Programmatic standpoint; and 2) UX standpoint.
  - You can use ErrorBoundaries to catch errors within the children components
  - Rather than letting the whole app crash you can catch the error at the component level (using getDerivedStateFromError and componentDidCatchError)
  - Components have state. Redux has/is state. 
- When do you decide whether to use component state or redux state?
- When you want to move state out of single components 
- How do you change the parents' state from a child component? Pass a function as props and call it
- What triggers a render cycle in React? Any time a prop changes that triggers a re-render, or the forceUpdate call
- When would you use a React pure component vs a stateless function?
  - https://medium.com/@ktajpuri/pure-react-component-vs-functional-react-component-with-a-simple-demo-a1c5129a2c03 
  - Parent and child render in a functional component
  - Pure component only renders if its own props change (shallow comparison)
  - Extend React.PureComponent
- When building a RESTful API or consuming it can you describe how your endpoints would map for a resource?
- How do you specify different levels of logging?
- Have you ever heard the term "dangerously set inner html?" What is it for? Similar to innerhtml
- Do you have much experience with code reviews?
  - What's the limit on Higher-Order Components you can use? 
- There isn't one, it's a trick question.
- What do you want to do? Where do you see yourself in a year?

## Company B
 
- Flexbox, CSS Grids, CSS Variables
- Array.filter, reduce, map, sort -> setState in React example
- Use JavaScript to get distance between two points
```js
filterPoets = (poetFilter) => {
   let filteredPoets = this.state.poets
   filteredPoets = filteredPoets.filter((poet) => {
     let poetName = poet.firstName.toLowerCase() + poet.lastName.toLowerCase()
     return poetName.indexOf(
       poetFilter.toLowerCase()) !== -1
   })
   this.setState({
     filteredPoets
   })
 }
```
  
## Company C

Implement a Hash Table in JS
  - https://www.mattzeunert.com/2017/02/01/implementing-a-hash-table-in-javascript.html

## Other

- Fizz / Buzz -- add up an element by 1 to 100; for every 3rd and 5th element, output fizz, buzz respectively
- PHP → Use classes methods to solve
- Use Javascript & CSS -- to open / close folders (no JQuery) from a PHP output
- Build a website for us using this PSD
- Javascript Test (1 hour)-- via Collabedit -- see sample JS Test
- Reverse a string without using built in functions
- Write a map, filter and reduce method in JS
- Create a sort method using JavaScript or PHP without calling a built in function
- Can use double for loops or a do while loop with flag (true and false) w/swap