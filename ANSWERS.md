- [ ] Why would you use class component over function components (removing hooks from the question)?

        We should use class components whenever we need to implement logic or state, while main usage of function components is displaying UI and rendering data passed via props from class components. Also, class component lets us use the react lifecycle methods.

- [ ] Name three lifecycle methods and their purposes.

        Constructor() used to initialize our class with the data; used to load in initial state data.
        Render() when triggered UI gets rendered to the DOM as it gives JSX code to the dome. The render() method is involved in mounting phase and updating phase.
        ComponentDidMount() is a method called once in the component life cycle, it as a place to make o make API calls as the component is already mounted.

- [ ] What is the purpose of a custom hook?

        Custom hooks are hooks built by ourselves that let us extract components logic into the functions that can be used by other components.

- [ ] Why is it important to test our apps?
      It is important to test our apps because we want to be able to provide the best app possible that has as little problems as it can for our users. Testing as we go can locate more bugs so that we can fix them faster instead of waiting until the end.
