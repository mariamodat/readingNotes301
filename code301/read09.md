# What is functional programming?
Functional programming languages are specially designed to handle symbolic computation and list processing applications. Functional programming is based on mathematical functions. Some of the popular functional programming languages include: Lisp, Python, Erlang, Haskell, Clojure, etc.
 # What is a pure function and how do we know if something is a pure function?
  The Pure function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.

  # what is immutability in programming
  In object-oriented and functional programming, an immutable object (unchangeable object) is an object whose state cannot be modified after it is created. ... For example, an object that uses memoization to cache the results of expensive computations could still be considered an immutable object.

  # what is referential transparency in functional programming
  In functional programming, referential transparency is generally defined as the fact that an expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program.

  # What is a module?
  a set of related functions and components semantically related with its own functional responsibility. They have all the assets they need to work on their own and can be tested independently of the rest of the application.
  ![img](https://cdn-media-1.freecodecamp.org/images/1*tZaoIiIYEv0bc0bLO-CYVg.png)

  The require function is intended to add separate pieces of code (“modules”) to the current scope, a feature that was not part of the JavaScript/ECMAScript language until the ES2015 specification.
  ### How do we bring another module into the file the we are working in?
  by export it then require it in the needed file.
  ![img](https://csharpcorner.azureedge.net/article/require-in-node-js/Images/image001.png)