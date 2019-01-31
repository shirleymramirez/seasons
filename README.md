***Component Life Cycle***

- Contructor - Good place to do state initialization, to do one time setup, can do some initial loading as well. But it is recommended to do data loading inside componentDidMount only.

- Render - return some JSX.

  -*content will be on the screen*

- componentDidMount - perfect location to do data loading. 

  -*sit and wait for updates*

- componentDidUpdate - called every single time our component is updated for any reason. It will be called every single time sample a - button is clicked or a text is inputted. Good to do more data loading when state or props change.

  -*sit and wait until this component is no longer shown*

- componentWillUnmount - good place to do cleanup


***How This Code Works:***
- So we have months of the year as:
  ![screenshot 3](https://user-images.githubusercontent.com/31137669/52003817-c91d4d80-2482-11e9-8bb3-3ac74935342a.png)


- Using new Date().getMonth() to get the current month and passed it as a parameter to the getSeason function, a logic test is done such that:  
  --a. if month is  greater than 2 and less than 9 and
  
  --b. lat is greater that 0, then, 
  
  --c. using ternary operation, 
  
   --**lat > 0 ? "summer" : "winter";**, if it is true, season will be summer, else, winter
    

- ![screenshot 6](https://user-images.githubusercontent.com/31137669/52004667-e8b57580-2484-11e9-9bda-036060cb0e52.png)

- So,
- ![screenshot 8](https://user-images.githubusercontent.com/31137669/52009219-a34a7580-248f-11e9-9a34-7c8b8c93157c.png)

- App will display like below:

- ![screenshot 10](https://user-images.githubusercontent.com/31137669/52009439-2f5c9d00-2490-11e9-8e4d-1a5824768459.png)

- else if 

- ![screenshot 11](https://user-images.githubusercontent.com/31137669/52009533-7054b180-2490-11e9-82bd-96a1ca8aeab9.png)

- the display will be like:

- ![screenshot 13](https://user-images.githubusercontent.com/31137669/52009654-b01b9900-2490-11e9-9077-ce0fd6af2a50.png)





