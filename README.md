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

5	When to use a Class Component over a Function Component?
answer: if we need states and lifecycle methods use class component otherwise we use functional components.

6	What are Pure Components?
answer: pure components not re-render when the current state or props and previous state or props are same.it done should component update lifecycle itself.
i.e it shallow compares the previous state or props to current state or props itself.

7	What is state in React?
answer: state is a piece of information in object form present in the component.the state can chsnge over a time by user action or system events.
 the component re-render when change in state.
 
8	What are props in React?
answer:props are the input to the component.it cannot be changed by child components. they are data passed down by parent component.
it can only changed in parent component.

9	What is the difference between state and props?
answer: 
*state can update inside the component where props can only update by parent component.
*state is similiar as variable declare in function where props are parameters passed to the function.
*props are read-only and immutable where state are mutable and change by user action.

10	Why should we not update the state directly?
answer: update state directly does not re-render the component and causes errors.

11	What is the purpose of callback function as an argument of setState()?
answer: it is used to make updates after state changes.

12	What is the difference between HTML and React event handling?
answer: * in html,we specify in lower case convention whereas in react, we use camel case convention.
*in html we need to function call for event handler where as in react, we just declare the variable.
*you can use false to prevent default behavior in html whereas in react we definr prevent default method.

13	What are synthetic events in React?
answer:all events in react are synthetic events.it is used for cross browser support.

14	What is "key" prop and what is the benefit of using it in arrays of elements?
answer:key props used to identify which element in array is changed.

15	What is the use of refs?
answer: it is used for direct to access dom.it isused in in changing value to child without use of props. 

20	How to create refs?

16	What are forward refs?
answer: passing ref further to its child  is ref forwarding.it is mostly used for reuseable components.

22	Which is preferred option with in callback refs and findDOMNode()?
23	Why are String Refs legacy?

17	What is Virtual DOM?
answer:virtual dom is the memory representation of real dom.

18	How Virtual DOM works?
answer: * any data changes in component the entire ui is re-rendered in virtual dom.
        * then it compares current and previous dom.
        * any  re-render the real dom where any data really changes.
        
19	What is the difference between Shadow DOM and Virtual DOM?
answer: shadow dom is browser technique for scoping variables and css. wheras virtual dom is libraries technique to avoid unwanted changes on real dom.

20	What is React Fiber?
answer: react fiber is the reconciliation technique or reimplementation technique.its main goal to increase suitability in animation,layout and gestures.

21	What is the main goal of React Fiber?

22	What are controlled components?
answer: the form data is controlled by component.every state change with its own event handler. 
23	What are uncontrolled components?
answer:the form data controlled by dom.every state change can use a ref to get form values from the DOM.

24	What is Lifting State Up in React?
answer:two child components share the same data from its parent, then move the state to parent instead of maintaining local state in both of the child components.

25	What are the different phases of component lifecycle?
 answer:       *mounting
               *updating
               *unmounting
               
26	What are the lifecycle methods of React?
answer:
            *componentwillmount
            *componentdidmount     
            *getDerivedStateFromProps
            *shouldcomponentupdate
            *componentwillupdate
            *componentWillReceiveProps
            *componentdidupdate
            *componentwillunmount
            
27	What are Higher-Order components?
answer:  higher-order component is a function that takes a component and returns a new component. it is a pattern that emerges from React???s compositional nature

28	What is context?
answer:context is used to pass a data through a component tree without passing props.for example, authentication it is used over many components.

29	What is children prop?
answer: it is used to pass the other component as data like other props in component.Component tree put between component's opening and closing tag will be passed to that component as children prop.

30	What is the purpose of using super constructor with props argument?
answer: constructor with super props is used to pass the 'this.props' variable to its child component.

31	What is reconciliation?
answer: components state or props change,it compares it with previous one.there is changes occurs re-renders the dom.this process is reconciliation.

32	Why React uses className over class attribute?
33	What are fragments?
answer: fragment is used to group the list of children without creating a extra node to the dom.

34	Why fragments are better than container divs?
answer:*fragments of faster than divs beacuse it cannot create extra node to dom.
*mechanisms in css like  Flexbox and CSS Grid . adding divs in the middle makes it hard to keep the desired layout. 

35	What are portals in React?
answer:Portal is a way to render children into a DOM node that exists outside the DOM hierarchy of the parent component.

36	What are stateless components?
answer:the component that independent of state is stateless component.it either class or functional component.

37	What are stateful components?
answer:the component that depends on its state are called statefull component.it is always class component.

38	How to apply validation on props in React?
39	What are the advantages of React?
answer: *it renders in clint and server sides
*Increases the application's performance with Virtual DOM.
*JSX makes code easy to read and write.
*easy to integrate with frameworks like angular.

40	What are the limitations of React?
answer:*React is just a view library, not a full framework.
*Integrating React into a traditional MVC framework requires some additional configuration.
*The code complexity increases with inline templating and JSX.

41	What are error boundaries in React v16
answer:Error boundaries are components that catch JavaScript errors anywhere in their child component tree, log those errors.

42	What are the recommended ways for static type checking?
answer:we use proptype library for type checking.in larger code we use flow or typescript.

43	What is the use of react-dom package?

44	What is the purpose of render method of react-dom?
answer:it is used to render  react element into the dom in giiven container,if element is rendered,it updates that element and mutate the dom according to it changes.

45	What is ReactDOMServer?
60	How to use InnerHtml in React?
61	How to use styles in React?
62	How events are different in React?
answer:*React event handlers are named using camelCase than lowercase.
*With JSX you pass a function as the event handler, rather than a string.

63	What will happen if you use setState in constructor?
answer:it gives error like 'Can only update a mounted or mounting component'.we only initialize state in constructor using 'this.state'.

64	What is the impact of indexes as keys?
answer:keys should be unique,stable for tract elements. using indexes for keys if the order of items may change and causes issues with component state.  
65	Is it good to use setState() in componentWillMount() method?
66	What will happen if you use props in initial state?
67	How do you conditionally render components?
answer:In some cases you want to render different components depending on some state. we use conditional shortcircuiting to render.

68	Why we need to be careful when spreading props on DOM elements?
answer:When we spread props we run into the risk of adding unknown HTML attributes. 
Instead we can use prop destructuring with ...rest operator, so it will add only required props.

69	How you use decorators in React?
answer:Decorators in React help you take an existing Class component, or function of a Class component, and modify it, thereby allowing you to add extra capabilities, without having to mess with the existing code.

70	How do you memoize a component?
answer:we can memoize component using moize library or using react.memo in latest react version v16.6.0.

71	How you implement Server-Side Rendering or SSR?
72	How to enable production mode in React?
73	What is CRA and its benefits?
The create-react-app CLI tool allows you to quickly create & run React applications with no configuration step.it includes everything need to build react app.

74	What is the lifecycle methods order in mounting?
answer:*constructor
*componentwillmount
*getDerivedStateFromProps
*render
*componentdidmount

75	What are the lifecycle methods going to be deprecated in React v16?
answer:
*componentWillMount
*componentWillReceiveProps
*componentWillUpdate

76	What is the purpose of getDerivedStateFromProps() lifecycle method?
answer: getDerivedStateFromProps is invoked right before calling the render method, both on the initial mount and on subsequent updates. It should return an object to update the state, or null to update nothing.

77	What is the purpose of getSnapshotBeforeUpdate() lifecycle method?
answer: The new getSnapshotBeforeUpdate() lifecycle method is called right before DOM updates. The return value from this method will be passed as the third parameter to componentDidUpdate().

78	Do Hooks replace render props and higher order components?
79	What is the recommended way for naming components?
80	What is the recommended ordering of methods in component class?
81	What is a switching component?
answer:A switching component is a component that renders one of many components. We need to use object to map prop values to components.

82	Why we need to pass a function to setState()?
83	What is strict mode in React?
84	What are React Mixins?
85	Why is isMounted() an anti-pattern and what is the proper solution?
86	What are the Pointer Events supported in React?
87	Why should component names start with capital letter?
answer:the name of component has to begin with a capital letter otherwise React will throw an error as unrecognized tag. This convention is because only HTML elements and SVG tags can begin with a lowercase letter.

88	Are custom DOM attributes supported in React v16?
89	What is the difference between constructor and getInitialState?
90	Can you force a component to re-render without calling setState?
answer:we can re-render the comonent without setstate() using forceupdate() method.

91	What is the difference between super() and super(props) in React using ES6 classes?
92	How to loop inside JSX?
answer: we can loop inside jsx using map method.
93	How do you access props in attribute quotes?
94	What is React PropType array with shape?
95	How to conditionally apply class attributes?
96	What is the difference between React and ReactDOM?
answer: React package contains the helpers for element and component of react whereas ReactDOM package contains the helpers for the react dom.

97	Why ReactDOM is separated from React?
answer: reactDom contains only the dom related features as a seperate library.

98	How to use React label element?
99	How to combine multiple inline style objects?
answer:you can combine inline style using spread operator.example: <button style={{...styles.panel.button, ...styles.panel.submitButton}}>{'Submit'}</button>
100	How to re-render the view when the browser is resized?
answer:You can listen to the resize event in componentDidMount() and then update the dimensions (width and height). You should remove the listener in componentWillUnmount() method.
example:  componentDidMount() {
    window.addEventListener('resize', this.updateDimensions)
  }

  componentWillUnmount() {
    window.removeEventListener('resize', this.updateDimensions)
  }

101	What is the difference between setState and replaceState methods?
answer: setstate merges current state with previous state. replacestate throws out the current state, and replaces it with only what you provide.
set false/null to setstate act as replacestate.

102	How to listen to state changes?
103	What is the recommended approach of removing an array element in react state?
answer: we can use array.filter method to remove the array element from state.
example: removeItem(index) {
  this.setState({
    data: this.state.data.filter((item, i) => i !== index)
  })
}
  
104	Is it possible to use React without rendering HTML?
105	How to pretty print JSON with React?
106	Why you can't update props in React?
answer:The React props should be immutable and top-down. This means that a parent can send any prop values to a child, but the child can't modify received props.

107	How to focus an input element on page load?
108	What are the possible ways of updating objects in state?
110	How can we find the version of React at runtime in the browser?
answer:You can use React.version to get the version.

111	What are the approaches to include polyfills in your create-react-app?
answer:
*Manual import from core-js
*Using Polyfill service using polyfill.io CDN

112	How to use https instead of http in create-react-app?
answer:You just need to use HTTPS=true configuration. 
*You can edit your package.json scripts section:
"scripts": {
  "start": "set HTTPS=true && react-scripts start"
}

* just run set HTTPS=true && npm start
* 
113	How to avoid using relative path imports in create-react-app?
answer:Create a file called .env in the project root and write the import path 'NODE_PATH=src/app'.
After that restart the development server,you should be able to import anything inside src/app without relative paths.

114	How to add Google Analytics for react-router?
answer: 
Add a listener on the history object to record each page view:
history.listen(function (location) {
  window.ga('set', 'page', location.pathname + location.search)
  window.ga('send', 'pageview', location.pathname + location.search)
})

115	How to update a component every second?
answer:You need to use setInterval() to trigger the change, but you also need to clear the timer when the component unmounts to prevent errors and memory leaks.

componentDidMount() {
  this.interval = setInterval(() => this.setState({ time: Date.now() }), 1000)
}
componentWillUnmount() {
  clearInterval(this.interval)
}

116	How do you apply vendor prefixes to inline styles in React?
117	How to import and export components using react and ES6?
118	What are the exceptions on React component naming?
119	Why is a component constructor called only once?
120	How to define constants in React?
121	How to programmatically trigger click event in React?
answer:This can be done in two steps:
*Create ref in render method:
<input ref={input => this.inputElement = input} />
*Apply click event in your event handler:
this.inputElement.click()

122	Is it possible to use async/await in plain React?
123	What are the common folder structures for React?
124	What are the popular packages for animation?
answer:React Transition Group and React Motion are popular animation packages in React ecosystem.

125	What is the benefit of styles modules?
126	What are the popular React-specific linters?
127	How to make AJAX call and In which component lifecycle methods should I make an AJAX call?
answer: You can use AJAX libraries such as Axios, jQuery AJAX, and the browser built-in fetch. You should fetch data in the componentDidMount() lifecycle method. This is so you can use setState() to update your component when the data is retrieved.

128	What are render props?
answer: Render Props is a simple technique for sharing code between components using a prop whose value is a function

                            react routers
129	What is React Router?
answer:Routing is a process in which a user is directed to different pages based on their action or request.
react router is the standard library for use routing in react.it is usually used in single pageapplcations(SPA).

130	How React Router is different from history library?

131	What are the <Router> components of React Router v4?
  *browser router
  *hash router
  *memory router
  
132	What is the purpose of push and replace methods of history?
  answer: *push method add new location to the history
  *replace method change current location from history to given one.
  
133	How do you programmatically navigate using React router v4?
134	How to get query parameters in React Router v4
135	Why you get "Router may have only one child element" warning?
  answer: You have to wrap your Route's in a <Switch> block because <Switch> is unique in that it renders a route exclusively.

136	How to pass params to history.push method in React Router v4?
137	How to implement default or NotFound page?
  answer:A Switch renders the first child Route that matches.we use the default or not found page component at last element inside the switch 
138	How to get history on React Router v4?
139	How to perform automatic redirect after login?                     
answer:<redirect> component is used to navigating new location, new location will override the current location in the history stack.

                                          react-redux
153	What is Redux?
  answer:redux is the open source javascript library used for application state management.it is a predictable state container for javascript apps.
  
154	What are the core principles of Redux?
  answer
  *single source of truth:it comtains single store thst stores the entire state for application.it is easier to keep track and update state.
  *state is read-only:we can change state only by emiting action that contains object tells what happened. 
  *Changes are made with pure functions:Reducers are just pure functions that take the previous state and an action as parameters, and return the next state.

  155	What are the downsides of Redux compared to Flux?
156	What is the difference between mapStateToProps() and mapDispatchToProps()?
  answer: mapStateToProps() is a utility which helps your component get updated state (which is updated by some other components):
mapDispatchToProps() is a utility which will help your component to fire an action event (dispatching action which may cause change of application state):

157	Can I dispatch an action in reducer?
  answer: dispatching action in reducer is anti-pattern.the reducers should without side effects.
  
158	How to access Redux store outside a component?
  answer:we just export the module where we create store using createStore() method.
  
159	What are the drawbacks of MVW pattern?
  answer:
  *DOM manipulation is very expensive which causes applications to behave slow and inefficient.
  *Due to circular dependencies, a complicated model was created around models and views.
  *Lot of data changes happens for collaborative applications(like Google Docs).
  *No way to do undo easily without adding so much extra code.
  
160	Are there any similarities between Redux and RxJS?
  answer: Redux is a tool for managing state throughout the application.it is an alternative to (half of) Angular. RxJS is a reactive programming library. It is usually used as a tool to accomplish asynchronous tasks in JavaScript. Think of it as an alternative to Promises. Redux uses the Reactive paradigm because the Store is reactive. The Store observes actions from a distance, and changes itself. RxJS also uses the Reactive paradigm, but instead of being an architecture, it gives you basic building blocks, Observables, to accomplish this pattern.

161	How to dispatch an action on load?
  answer: we can dispatch action in componentDidMount() method and in render() method you can verify the data.
  
162	How to use connect from React Redux?
  answer:Use mapStateToProps(): It maps the state variables from your store to the props that you specify.
Connect the above props to your container: The object returned by the mapStateToProps function is connected to the container. You can import connect() from react-redux.
  
163	How to reset state in Redux?
  answer: The root reducer would normally delegate handling the action to the reducer generated by combineReducers().
  
164	Whats the purpose of at symbol in the redux connect decorator?
  answer:The @ symbol is in fact a JavaScript expression used to signify decorators. Decorators make it possible to annotate and modify classes and properties at design time.
  
165	What is the difference between React context and React Redux?
166	Why are Redux state functions called reducers?  
  answer:Reducers always return the accumulation of the state (based on all previous and current actions). they act as a reducer of state. Each time a Redux reducer is called, the state and action are passed as parameters. This state is then reduced (or accumulated) based on the action, and then the next state is returned. You could reduce a collection of actions and an initial state (of the store) on which to perform these actions to get the resulting final state.

167	How to make AJAX request in Redux?
  You can use redux-thunk middleware which allows you to define async actions.

168	Should I keep all component's state in Redux store?
  answer:Keep your data in the Redux store, and the UI related state internally in the component.

169	What is the proper way to access Redux store?
  answer: we can access your store in a component by the connect() function, that creates a new component that wraps around your existing one.
   This allows you to map state and action creators to your component, and have them passed in automatically as your store updates.
  
170	What is the difference between component and container in React Redux?
  answer:
  *Component is a class or function component that describes the presentational part of your application.
  *Container is a component that is connected to a Redux store. Containers subscribe to Redux state updates and dispatch actions, and they don't render DOM elements;
  
171	What is the purpose of the constants in Redux?
  answer:Constants allows you to easily find all usages of that specific functionality across the project when you use an IDE. It also prevents you from introducing bugs caused by typos like ReferenceError.


172	What are the different ways to write mapDispatchToProps()?
173	What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()?
  
174	How to structure Redux top level directories?
  answer:
  *container
  *component
  *action 
  *reducers
  *store
  
175	What is redux-saga?
  answer:redux-saga is a library that aims to make side effects (asynchronous things like data fetching and accessing the browser cache) in React/Redux applications easier and better.
176	What is the mental model of redux-saga?
177	What are the differences between call and put in redux-saga
178	What is Redux Thunk?
  answer:Redux Thunk middleware allows you to write action creators that return a function instead of an action and it deals with side effects like  network calls. 
  The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. 
  The inner function receives the store methods dispatch() and getState() as parameters.
  
179	What are the differences between redux-saga and redux-thunk
  answer:
  *Both Redux Thunk and Redux Saga take care of dealing with side effects.
  *Thunk uses Promises to deal with them, whereas Saga uses Generators. 
  *Thunk is simple to use and Promises are familiar to many developers, Sagas/Generators are more powerful but you will need to learn them. 
  
180	What is Redux DevTools?
  annswer: Redux DevTools is a live-editing time travel environment for Redux with hot reloading, action replay, and customizable UI.
  you can use Redux DevTools Extension for Chrome and Firefox.
181	What are the features of Redux DevTools?
answer:
*Lets you inspect every state and action payload.
*Lets you go back in time by cancelling actions.
*If you change the reducer code, each staged action will be re-evaluated.
*If the reducers throw, you will see during which action this happened, and what the error was.
*With persistState() store enhancer, you can persist debug sessions across page reloads.
  
182	What are Redux selectors and Why to use them?
  answer:Selectors are functions that take Redux state as an argument and return some data to pass to the component.
  The selector can compute derived data, allowing Redux to store the minimal possible state
  The selector is not recomputed unless one of its arguments changes
  
183	What is Redux Form?
  answer:Redux Form works to enable a form in React to use Redux to store all of its state. Redux Form can be used with raw HTML5 inputs, it also works very well with common UI frameworks like Material UI, React Widgets and React Bootstrap.

184	What are the main features of Redux Form?
  answer:
  *Field values persistence via Redux store.
  *Validation (sync/async) and submission.
  *Formatting, parsing and normalization of field values.
  
185	How to add multiple middlewares to Redux?
  answer:You can use applyMiddleware().
 example: you can add redux-thunk and logger passing them as arguments to applyMiddleware():

  const createStoreWithMiddleware = applyMiddleware(ReduxThunk, logger)(createStore)

186	How to set initial state in Redux?
  answer:You need to pass initial state as second argument to createStore:
example:const store = createStore(
  rootReducer,
  initialState
)
  
187	How Relay is different from Redux?
  answer: Relay is similar to Redux in that they both use a single store. The main difference is that relay only manages state originated from the server, and all access to the state is used via GraphQL queries (for reading data) and mutations (for changing data). Relay caches the data for you and optimizes data fetching for you, by fetching only changed data and nothing more.

188	What is an action in Redux?
  answer: actions are javascript objects or payload send from your application to redux store. They are the only source of information for the store. 
  Actions must have a type property that indicates the type of action being performed.
