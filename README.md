react js sound byte answer

1	What is React?
answer: React is the open source javascript library used for creating single page applications.

2	What are the major features of React?
   * uses virtual DOM because realDOM manipulations are expensive 
   * unidirectional dataflow i.e props are passed to the children.
   * reuseable components  
   
3	What is JSX?
answer: javascript extension syntax used to write html and javascript into react easily.jsx-javascript XML.

4	What is the difference between Element and Component?

5	How to create components in React?
6	When to use a Class Component over a Function Component?
answer: if we need states and lifecycle methods use class component otherwise we use functional components.
7	What are Pure Components?
answer: pure components not re-render when the current state or props and previous state or props are same.it done should component update lifecycle itself.
i.e it shallow compares the previous state or props to current state or props itself.

8	What is state in React?
answer: state is a piece of information in object form present in the component.the state can chsnge over a time by user action or system events.
 the component re-render when change in state.
 
9	What are props in React?
answer:props are the input to the component.it cannot be changed by child components. they are data passed down by parent component.
it can only changed in parent component.

10	What is the difference between state and props?
answer: 
*state can update inside the component where props can only update by parent component.
*state is similiar as variable declare in function where props are parameters passed to the function.
*props are read-only and immutable where state are mutable and change by user action.

11	Why should we not update the state directly?
answer: update state directly not re-rener th component and causes errors.

12	What is the purpose of callback function as an argument of setState()?
answer: it is used to make updates after state changes.

13	What is the difference between HTML and React event handling?
answer: * in html,we specify in lower case convention whereas in react, we use camel case convention.
*in html we need to function call for event handler where as in react, we just declare the variable.
*you can use false to prevent default behavior in html whereas in react we definr prevent default method.

14	How to bind methods or event handlers in JSX callbacks?
15	How to pass a parameter to an event handler or callback?
16	What are synthetic events in React?
answer:all events in react are synthetic events.it is used for cross browser support.
17	What are inline conditional expressions?
18	What is "key" prop and what is the benefit of using it in arrays of elements?
answer:key props used to identify which element in array is changed.

19	What is the use of refs?
answer: it is used to access dom directly without passing through the components.
20	How to create refs?
21	What are forward refs?
22	Which is preferred option with in callback refs and findDOMNode()?
23	Why are String Refs legacy?
24	What is Virtual DOM?
25	How Virtual DOM works?
