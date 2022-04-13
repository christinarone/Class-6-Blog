# Class-6-Blog
Describe one thing you're learning in class today.
  I learned how to play the Towers of Hanoi game. I had never heard of this game. I find it easy to understand the game, but coding it is difficult.

What's the difference between: function Person(){}, var person = Person(), and var person = new Person()?

  function Person(){} <Function declaration> is just a normal function declaration (it declares the function but doesn't execute it.) It does get             registered into the global namespace.
  
  var person = Person() <Function Expression> (always returns a value) It contains a value reference to a Person function.
  
  var person = new Person()<Function Constructor> By adding the keyword 'new', we are instantiating a new object of the Person class constructor. A            function declaration is just a regular function unless it has been instantiated, it then becomes a class constructor.

What's the difference between an "attribute" and a "property"?
  
  An attribute (defined by HTML; the value is constant)is the initial state when rendered in the DOM. A property (defined by the DOM; the value of a property is variable)is the current state. 


What language constructions do you use for iterating over object properties and array items?
    You can use the forEach() method along with the forLoop method.

What is the event loop?
      The event loop has one simple job-- to monitor the Call Stack and the Callback Queue. It has the responsibility to see whether the call-stack is empty and does the task queue contain a pending task to process. If the call-stack is empty, it will push back the task to the call-stack from the queue and then the task gets processed. 


What is the difference between call stack and task queue?
      Call stack is a data structure which keeps track of function calls in our program.
      Task queue handles the Web Apis callbacks. The messages are processed once the call stack is clear.


What are the differences between ES6 classes and ES5 function constructors?
    ES6 class basically does the work of defining a new object and appending functions to its prototype.
    ES5 Function constructors work and look the same but the main difference is observed when the developer uses the inheritance property.
