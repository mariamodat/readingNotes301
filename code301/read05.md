# Thinking in React
React is a declarative JavaScript library for building user interfaces. What I mean by declarative is that it does what you tell it to do, rather than describing control flow. Learning React can be fun and challenging at the same time. The great power lies in using the React concept the right way. React documentation has a nice article about the thought process of building apps which I recommend.

![img](https://miro.medium.com/max/1705/1*Dee4cg5Hzg7JME1A9tjZJQ.png)
![img](https://image.slidesharecdn.com/react-170126232952/95/reactredux-16-638.jpg?cb=1485473573)


# static
React Static is a modern static-site generator built for the React ecosystem, with a focus on flexible, data-agnostic, tooling. It provides SSR (server-side rendering), code-splitting, automatic prefetching, and more out-of-the-box.

To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.
## What are the three questions you can ask to determine if something is state?
* The original list of products
* The search text the user has entered
* The value of the checkbox
* The filtered list of products