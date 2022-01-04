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
answer: update state directly does not re-render the component and causes errors.

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
answer: it is used for direct to access dom.it isused in in changing value to child without use of props. 

20	How to create refs?

21	What are forward refs?
answer: passing ref further to its child  is ref forwarding.it is mostly used for reuseable components.

22	Which is preferred option with in callback refs and findDOMNode()?
23	Why are String Refs legacy?

24	What is Virtual DOM?
answer:virtual dom is the memory representation of real dom.
25	How Virtual DOM works?
answer: * any data changes in component the entire ui is re-rendered in virtual dom.
        * then it compares current and previous dom.
        * any  re-render the real dom where any data really changes.
        
26	What is the difference between Shadow DOM and Virtual DOM?
answer: shadow dom is browser technique for scoping variables and css. wheras virtual dom is libraries technique to avoid unwanted changes on real dom.

27	What is React Fiber?
answer: react fiber is the reconciliation technique or reimplementation technique.its main goal to increase suitability in animation,layout and gestures.

28	What is the main goal of React Fiber?

29	What are controlled components?
answer: the form data is controlled by component.every state change with its own event handler. 
30	What are uncontrolled components?
answer:the form data controlled by dom.every state change can use a ref to get form values from the DOM.

31	What is the difference between createElement and cloneElement?
32	What is Lifting State Up in React?
answer:two child components share the same data from its parent, then move the state to parent instead of maintaining local state in both of the child components.

33	What are the different phases of component lifecycle?
 answer:       *mounting
               *updating
               *unmounting
               
34	What are the lifecycle methods of React?
answer:
            *componentwillmount
            *componentdidmount     
            *getDerivedStateFromProps
            *shouldcomponentupdate
            *componentwillupdate
            *componentWillReceiveProps
            *componentdidupdate
            *componentwillunmount
            
35	What are Higher-Order components?
answer:  higher-order component is a function that takes a component and returns a new component. it is a pattern that emerges from React’s compositional nature

36	How to create props proxy for HOC component?

37	What is context?
answer:context is used to pass a data through a component tree without passing props.for example, authentication it is used over many components.

38	What is children prop?
answer: it is used to pass the other component as data like other props in component.Component tree put between component's opening and closing tag will be passed to that component as children prop.

39	How to write comments in React?

40	What is the purpose of using super constructor with props argument?
answer: constructor with super props is used to pass the 'this.props' variable to its child component.

41	What is reconciliation?
answer: components state or props change,it compares it with previous one.there is changes occurs re-renders the dom.this process is reconciliation.

42	How to set state with a dynamic key name?

43	What would be the common mistake of function being called every time the component renders?
44	Is lazy function supports named exports?
45	Why React uses className over class attribute?
46	What are fragments?
answer: fragment is used to group the list of children without creating a extra node to the dom.

47	Why fragments are better than container divs?
answer:*fragments of faster than divs beacuse it cannot create extra node to dom.
*mechanisms in css like  Flexbox and CSS Grid . adding divs in the middle makes it hard to keep the desired layout. 

48	What are portals in React?
answer:Portal is a way to render children into a DOM node that exists outside the DOM hierarchy of the parent component.

49	What are stateless components?
answer:the component that independent of state is stateless component.it either class or functional component.

50	What are stateful components?
answer:the component that depends on its state are called statefull component.it is always class component.

51	How to apply validation on props in React?
52	What are the advantages of React?
answer: *it renders in clint and server sides
*Increases the application's performance with Virtual DOM.
*JSX makes code easy to read and write.
*easy to integrate with frameworks like angular.

53	What are the limitations of React?
answer:*React is just a view library, not a full framework.
*Integrating React into a traditional MVC framework requires some additional configuration.
*The code complexity increases with inline templating and JSX.

54	What are error boundaries in React v16
answer:Error boundaries are components that catch JavaScript errors anywhere in their child component tree, log those errors.
55	How error boundaries handled in React v15?
56	What are the recommended ways for static type checking?
57	What is the use of react-dom package?
58	What is the purpose of render method of react-dom?
59	What is ReactDOMServer?
60	How to use InnerHtml in React?
61	How to use styles in React?
62	How events are different in React?
