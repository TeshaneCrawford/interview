# interview questions, React

1. **What is JSX?**

    JSX is a XML-like syntax extension to ECMAScript. Basically it just provides syntactic sugar for the React.createElement() function, giving us expressiveness of JavaScript along with HTML like template syntax.

2. **What is the difference between Element and Component?**

    An Element describes what appears on screen, it is never mutated. Whereas a component can be declared in several different ways. It can be a class with a render() method or it can be defined as a function. In either case, it takes props as an input, and returns a JSX tree.

3. **When to use a Class Component over a Function Component?**

    If the component needs state or lifecycle methods then use class component otherwise use function component. But it is recommened to use Function components instead.

4. **What is state in React?**

    State of a component is an object that holds some information that may change over the lifetime of the component. We should always try to make our state as simple as possible and minimize the number of stateful components.

5. **What are props in React?**

    Props are the inputs to a component. They are passed as an object to the component. They're data passed downed from a parent component to a child component.

    The primary purpose of props in React is to provide following component functionality:

    i. Pass custom data to your component.

    ii. Trigger state changes.

    iii. Use via this.props.reactProp inside component's render() method.

6. **What is the difference between state and props?**

    State is the data that is stored in the component. Props is the data that is passed from the parent component to the child component.

7. **Why should we not update the state directly?**

    If you try to update the state directly then it won't re-render the component. You should always use setState() method to update the state. It schedules an update and when the state changes, the component responds by re-rendering itself.

8. **What is the difference between setState() and componentWillUpdate()?**

    setState() is used to update the state of the component. It is called by the component itself. It is called after the component has been rendered.
    componentWillUpdate() is called before the component is rendered. It is called before the component is updated.

9. **What is "key" in React?**

    Key is a property that is used to identify a component. It is used to uniquely identify a component in a list of components. Key prop helps React identify which items have changed, are added, or are removed.

10. **What is the difference between "key" and "ref"?**

    Key is used to uniquely identify a component in a list of components. Ref is used to reference a component in the DOM.

11. **What is the strictmode component and why would you use it?**

    StrictMode is a component included with React to provide additional visibility of potential issues in components. If the application is running in development mode, any issues are logged to the development console, but these warnings are not shown if the application is running in production mode.

    Developers use StrictMode to find problems such as deprecated lifecycle methods and legacy patterns, to ensure that all React components follow current best practices.

12. **What are controlled components and uncontrolled components?**

    Controlled components are components that have a value that is provided by the parent component. Uncontrolled components are components that have a value that is not provided by the parent component.

13. **What are the lifecycle methods in React?**

    Lifecycle methods are methods that are called by React when a component is rendered, updated, or unmounted.

14. **What is the difference between componentWillMount() and componentDidMount()?**

    componentWillMount() is called before the component is mounted. It is called before the component is rendered.
    componentDidMount() is called after the component is mounted. It is called after the component is rendered.

15. **What are Higher-Order Components?**

    Higher-order components are components that take other components as input and return a new component.

16. **What is the difference between Component and PureComponent?**

    Component is a class component. PureComponent is a functional component.

17. **What is Context?**

    Context is a way to share data between components without having to pass props down from one component to another. For example, authenticated users, locale preferences, UI themes need to be accessed in the application by many components.

18. **What is a children prop?**

    Children prop is a prop that is used to pass children to a component.

19. **What is reconciliation?**

    Reconciliation is the process of comparing the current tree of the component with the previous tree and updating the DOM to match the new tree.

20. **What is the difference between a render() method and a componentDidMount() method?**

    render() is called every time the component is rendered. componentDidMount() is called only once when the component is mounted.

21. **What are Fragments?**

    Fragments are used to group a list of children without adding extra nodes to the DOM.

22. **What are stateless functional components?**

    Stateless functional components are components that do not maintain any state. They are functions that take props as an input and return a JSX tree.

23. **What are stateful components?**

    Stateful components are components that maintain state. They are classes that have a render() method.

24. **What are render props?**

    Render Props is a simple technique for sharing code between components using a prop whose value is a function.

25. **What is the difference between a propTypes and a propTypes check?**

    propTypes is a static property that is used to validate the props of a component. propTypes check is a runtime check that is performed at runtime.

26. **What is React Router?**

    React Router is a powerful routing library built on top of React that helps you add new screens and flows to your application incredibly quickly, all while keeping the URL in sync with what's being displayed on the page.

27. **What is the difference between a route and a link?**

    A route is a path that is used to match a URL. A link is a component that is used to render a link to a route.

28. **What is styled components?**

    Styled components are a way to style your components using CSS in JS.

29. **What is React Hooks?**

    React Hooks is a set of new features that allow you to use state and other React features without writing a class.

30. **What is the difference between useState and useEffect?**

    useState is a hook that is used to create a state variable. useEffect is a hook that is used to add side effects to your component.

    useState is a function that returns an array of two elements. The first element is the current state of the state variable and the second element is a function that can be used to update the state variable.

31. **What is the difference between useContext and useReducer?**

    useContext is a hook that is used to access the context object. useReducer is a hook that is used to access the reducer object.

32. **Name a few techniques to optimize React app performance.**

    useMemo()

    Lazy loading

## Questions to ask interviewer

- How large is your team?
- What is your stack?
- Are rushes to deadlines common? Or is there flexibility?
- What does your dev cycle look like? Do you do waterfall/sprints/agile?
- What is the work life like?

## Resources

- **Links**

Frontend Interview Handbook: <https://www.frontendinterviewhandbook.com/introduction/>

### Contribution

Feel free to add a new branch and contribute

### Author

[**Teshane Crawford**](https://github.com/TeshaneCrawford)

