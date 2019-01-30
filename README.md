***Component Life Cycle 

- Contructor - Good place to do state initialization, to do one time setup, can do some initial loading as well. But it is recommended to do data loading inside componentDidMount only.
- Render - return some JSX.
- componentDidMount - perfect location to do data loading. 
- componentDidUpdate - called every single time our component is updated for any reason. it will be called every single time sample a - button is clicked or a text is inputted. Good to do more data loading when state or props change.
-componentWillUnmount - good place to do cleanup
