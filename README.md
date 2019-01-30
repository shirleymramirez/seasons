***Component Life Cycle***

- Contructor - Good place to do state initialization, to do one time setup, can do some initial loading as well. But it is recommended to do data loading inside componentDidMount only.

- Render - return some JSX.

  -*content will be on the screen*

- componentDidMount - perfect location to do data loading. 

  -*sit and wait for updates*

- componentDidUpdate - called every single time our component is updated for any reason. It will be called every single time sample a - button is clicked or a text is inputted. Good to do more data loading when state or props change.

  -*sit and wait until this component is no longer shown*

- componentWillUnmount - good place to do cleanup
