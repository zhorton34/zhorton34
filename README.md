### Hi there 👋


**zhorton34/zhorton34** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

[![Twitter Follow](https://img.shields.io/twitter/follow/cleancodestudio.svg?style=social)](https://twitter.com/cleancodestudio) 

---

 As JavaScript developers we strive towards clean, healthy, and maintainable code. We strive towards solving challenges eloquently. 


![JavaScript code picture - just decorator for blog](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o0wna1ohdcfvrlv57vw0.jpg)


While these challenges may each, within themselves, be unique - we don't necessarily require unique solutions for each individual one of these new challenges we face. 




---

>
> _"If you've used a solution that is not a unique solution to_ 
> _solve a challenge that is in of itself a unique challenge, then_ 
> _you have utilized the power of a JavaScript **design pattern**"_.
> 

---


Software languages have been around for decades. The life span of a software language is decently well understood at this point. During any language's lifespan, many such reusable solutions are made and tested by a large number of the developers within a given languages community. Through the power of compounded developer experience, solutions known as design patterns are created and made useful to the masses. These solutions support the creation of optimized ways to solve a large many of problem types based on a much lesser amount of design patterns. 

![woman on left and looking up at title of this article while kid on right points from the left side at the article text. The https://cleancode.studio url is floating right above the centered title that both the woman and the kid are looking up at.](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/heh63v01se1aqbsj99e6.png)

---



> _"Design patterns are reusable solutions to commonly occurring problems in software design"_


What benefits do we gain from design patterns?

---

- **Proven Solutions:** Many software developers use Design Patterns. Being used by many developers with success, we are provided with more certainty of our success when implementing a given design pattern. When a design pattern becomes main stream, you can have confidence in knowing that they have been revised and refactored multiple times over. Proven solutions are often times optimal, consider edge cases, and are utilized in a wide variety of use cases.

---

- **Easily Reusable:** When a solution is reusable, it can be modified to solve multiple particular problems. Design patterns document a reusable solution that is not coupled to any specific problem but rather a set of challenges that the design pattern assists in over coming.

---


- **Expressive:** Often times, design patterns can explain large solutions in a to the point and simplified way.

---

- **Lower the need for refactoring code:** Most design patterns take into account code dependencies, existing and future dependencies. The Open Closed Design Principle, for example - prevents the need to refactor code that is already written. Instead you create a new class (implement an interface in other non js languages) and add code. You limit the need to refactor code using design patterns.

---

- **Simplify Communication:** Teams built with software engineers who are familiar with design patterns are able to more easily communicate internally through the language of their code base. They are also able to communicate externally about potential solutions, future concerns worth noting, and over all architectural design. Design Patterns simplify communication.

---

- **Reduced Codebase site:** Due to their elegant, efficient, and well thought out approach, design patterns usually require less code and ultimately simply a team's code base.


> _"Before we dive in, let's breifly review the history of JavaScript to better understand the context in which many of our modern day design patterns were built."_

---

### A (Brief) JavaScript History Lesson

---

In the world of web development, JavaScript is one of the most popular programming languages out there today. 


In the beginning, JavaScript wasn't intended to be this impressive world wide accepted language with reactive front-ends, modularized code repositories, and millions of packages installable via npm. 

Not even close, in the beginning JavaScript was more like the "glue" that allowed you to stick various displays of HTML elements together. First known as a client-side scripting language, one of the worlds first web browsers - Netscape Navigator, utilized JavaScript display static HTML. 

This, of course, led to what we now know as **war of the browsers**. 

Browser's were new, hot, and exploding - they were that next big thing in the tech industry. Big players like Mozilla (Formerly known as Netscape Communications), Microsoft Explorer, and eventually Chrome battled it out for Browser glory.


As the driving force behind each Browser in this Browsers War - the big dogs were researching, developing, and creating new and improved ways to implement their own client-side scripting language.


- **Netscape:** JavaScript (Really, Brendan Eich created the original JS)

- **Microsoft:** JScript (Any one know what that is anymore?)

As a developer in that day in age, I image great frustrations. The implementations differed in great regards. Development wasn't for all browsers - but instead for individual browsers. 

As I imagine it, a heard of angry software engineers with pitch forks and torches gathered in numbers that rivaled the armies of our world histories most malicious wars. With out raged developers rising, we have one single demand - pick a MO**** FU***** language for all browsers. 

_(My imagination visualizes our developer ancestors during this era more as great viking warriors thirsty for war and to face death in the battle for simplification and glory. I've also been watching Vikings lately on Hulu - this may have my imagination running rampant...)_


Thus, [ECMAScript](https://en.wikipedia.org/wiki/ECMAScript) was born.

What was ECMAScript you ask? The cry of freedom, inclusivity, and standardization of non insanity.

ECMAScript is a standardized scripting language specification which all modern browsers try to support. It does have many implementations that are more like differing dialects if you want to make the traditional human language analogy. 

I like to think of ECMAScript as the original father of all scripting languages and JavaScript as it's heroic son - the hero of hero's, the fighter who beat all odds, and the one who lands all of the senorita's because it's awesome (But like seriously, [JavaScript is one of the languages most often used software languages by all of you senorita engineers](https://www.techrepublic.com/article/the-5-most-popular-programming-languages-among-female-developers/)) 

JavaScript was the most popular dialect that arose from ECMAScript. 

Since it's big bang into the world of reality, ECMAScript has done some important things for the software engineering community. It has standardized a lot of important things that is listed [here on Wikipedia](https://en.wikipedia.org/wiki/ECMAScript#Conformance).


Browser support for ECMAScript versions 6 (ES6) and higher are still incomplete and have to be transpiled to ES5 in order to be fully supported.

---

### What is JavaScript (Other than Awesome)?

---

Lets introduce some very important JavaScript language characteristics. You'll want some awareness and context around these attributes of JavaScript before diving into the JS Design Patterns talked about in this article.

---

**Hey - you! Reading this article. Here's a question for you...**

---

> _"What is JavaScript?"_



---
**One possible answer might be:**

> _"JavaScript is a lightweight, interpreted, object-oriented programming language with first-class functions most commonly known as a scripting language for web pages."_

Hmmm....

Huhhh?!


Basically, what this very overy complicated quote written by a person or persons much smarter than me meant to say is something like:

- JS has a low memory footprint
- JS is easy to implement
- JS is easy to learn
- JS has syntax similar to that of other popular languages such as C++ and Java
- JS is a scripting language
   - Which means its code is interpreted instead of compiled
- JS has procedural support
- JS has object-oriented support
- JS has functional programming styles support
- JS is flexible for developers! (Until S*** breaks, then it just hurts)


These would be the JavaScript attributes or characteristics that you will find in many other popular software languages -- but, as many of us know all to well, JavaScript is funky and goes to the beat of its own groove. 

---

### JavaScript Supports First-Class Functions

---

> _First class functions are incredibly powerful, but also somewhat difficult to grasp at first. A programming language is said to have First-class functions simply means that functions in that language are treated like any other variable._

- **First Class Functions Can Be:** Passed As Arguments to other functions

```js
/* We pass a function as the argument */
function action (name, payload, callback_function) {
    let context = { name, payload };

    callback_function(context);
};

action('log-alert', 'hello world', function (context) {
   console.log(
     "The action context: ", context, 
     "The action name: ", context.name, 
     "The action payload: ", context.payload
   );
})

```

- **First Class Functions Can Be:** Returned by another function
```js
function sayHello() {
   return function() {
      console.log("Hello!");
   }
}
```

- **First Class Functions Can Be:** Assigned as a value to a variable

```js
const foo = function() {
   console.log("foobar");
}
// Invoke it using the variable
foo();
```


---

### JavaScript Prototype Based

---

> _JavaScript is object-oriented - thus it supports objects. Now most non-familiar with JavaScript would logically think objects, then classes, and then maybe even inheritance._

JavaScript has a bit of a different approach...

> _Classes aren't supported in the plain form of JavaScript...instead JavaScript uses what is known as **Prototype-Based** or **Instance-Based** **Inheritance**_


In ES6, the term of **Class** was formally introduced. All browsers do fully support ES6 as this post is being written so we can use the **Class** keyword - but it still works differently in a prototypal language like JS.

**Prototype-based programming** 

- Style of object-oriented programming
 > _Behavior reuse (known as inheritance) is performed via a process of reusing existing objects via delegations that serve as prototypes_

- We dive deeper further down in the design patterns section of this article. Understanding prototypes is extremely important JS, but let's hold off on adding in too much detail just yet. 


---

### JavaScript Event Loops

---

Have you ever heard of a callback function? If you're used to working in the world of JavaScript I'm sure you have. 


A callback function is a function sent as a parameter (acceptable thanks to functions being first-class citizens) to another function. The function passed as a parameter is then called after an **event** fires. Often times, this is used for subscribing to events. 

![JavaScript Event Loop Diagram](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wxllvbaqsdulq0inns28.png)

Example: Right mouse click event triggers a function to be called - hence **callback function**


- An event has a listener attached to it.
- Each time that event fires (otherwise the event is lost)
- A message is sent to a queue of messages 
  - This queue (FIFO - first in first out) of message processes synchronously.

This process is what we know as the JavaScript **event loop.**


Each queue message 
- Has an associated function

Once the queue message is dequeued 
- The runtime executes the function completely before processing any other message.

If a function contains other function calls
- They are all performed prior to processing a new message from the queue. 

This is called **run-to-completion**




```js
while (queue.waitForMessage()) 
{
    queue.processNextMessage();
}
```

**queue.waitForMessage()**
- Synchronously waits for new messages.
  - Each of the messages being processed has its own stack
    - And is processed until the stack is empty.
      - Once finished processing
        - A new message is processed from the queue (if there is one)


---

#### Are you a fan of Clean Code Studio's content?

> "Join the newsletter for more content like this!"


{% codepen https://codepen.io/zhorton34/pen/BaRPYdB %}


---

> _Have you ever heard the terminology of "non-blocking" or asynchronous used in reference to JavaScript?_

When an async operation is executed
- It does not halt or stop the the runtime
- The program is able to process other things
   - Ex: Receiving user input
- While waiting for the asynchronous operation to finalize

Asynchronous operations are **non-blocking** to the main execution thread. 

This is an extremely useful ability both wielded internally by JavaScript while also usable externally for your specific JavaScript use cases. Async vs. Sync is a huge topic in JavaScript, but if we too dive deep into we'd never get to our 
design patterns - the topic in scope for this post.


---

### What are design patterns

---

> _Design patterns are reusable solutions to commonly occurring problems in software design. Let's take a look at some of the categories of design patterns_




---

#### Proto-patterns

---

Creating a design pattern, how do you do it? Do you notice any commonly re-occurring problem? Have you surmounted a solution you've uniquely designed to solve this problem? This solution of yours, let's say it's not globally recognized and documented. 

Every time this problem comes up or is encountered, you use this solution. This solution you've created is reusable and the developer community as a whole would be beneficiaries of such a pattern.

This would not immediately make it a design pattern. A programmer may have good code and simply mistake something that looks like a pattern for an actual design pattern - when, at the end of the day - it's not an actual design pattern.


**What makes something an actual design pattern?**

**Answer:** General developer consensus. 

If you're able to get opinions from a large number of developers you're on the right track. By knowing the process of creating a pattern itself, and by making yourself well acquainted with existing patterns you're beginning to learn that process. Any design pattern must go through this phase for it to become a full-fledged pattern. This is called a **proto-pattern.**


A **proto-pattern** is a pattern-to-be _if_ it meets the standards defined by a certain period of testing that it must undergo by a various number of developers. It must be tested within the context of many challenges, be analyzed within a number of scenarios, and ultimately the be proven a useful and re-usable design pattern via many tests and general community consensus. 

A large amount of work & documentation has been done in order to show what it takes to make a fully-fledged pattern recognized by the developer community of a given software language. 


---

### Anti-patterns

---

Also worth noting, like with many things in software, is the inverse of a given concept. What's the inverse of a design pattern? 

**Anti-patterns**

An **Anti-pattern** is representative of a bad practice. An example of an anti-pattern would be modifying the `Object` class prototype. 


In JavaScript, everything pretty much inherits from `Object`. JavaScript uses prototype-based inheritance so given any situation you have now changed a something. You've created a variation that could alter all other design-patterns, concepts, or techniques within JavaScript. This is no good and thus an **anti-design** pattern. 


---

### Design Pattern Categorization

---

Categorization of design patterns happens in a multitude of ways, but here's a popular breakdown.

- **Creational** design patterns
- **Structural** design patterns
- **Behavioral** design patterns
- **Concurrency** design patterns
- **Architectural** design patterns


--- 

#### Creational Design Patterns

---


Creational design patterns are patterns used to create objects. These are design patterns that optimize the mechanisms which create a single or group of objects.

- Builder Design Pattern
- Factory Design Pattern
- Singleton Design Pattern
- Prototype Design Pattern
- Abstract Factory Design Pattern

Are all examples of **Creational Design Patterns** 


---

#### Structural Design Patterns

---

Structural design patterns are related to object relationships. These kinds of design patterns ensure that if one part of a system changes, the entire system doesn't need to change along with it. 

- Proxy Design Pattern
- Bridge Design Pattern
- Facade Design Pattern
- Adapter Design Pattern
- Decorator Design Pattern
- Flyweight Design Pattern
- Composite Design Pattern

Are all examples of **Structural Design Patterns**.

---

#### Behavioral Design Patterns

---

Behavioral design patterns recognize, implement, and improve communication between contrasting objects in a system. They are used to support contrasting parts of a given software system have synchronized data. 


- State Design Pattern
- Visitor Design Pattern
- Command Design Pattern
- Memento Design Pattern
- Iterator Design Pattern
- Mediator Design Pattern
- Observer Design Pattern
- Strategy Design Pattern
- Chain of Responsibility Design Pattern

Are all examples of **Behavioral Design Patterns**.

---

#### Concurrency Design Patterns

---

Concurrency design patterns are utilized to implement solutions for multi-threaded programming paradigms. 


- Scheduler Design Pattern
- Active Object Design Pattern
- Nuclear Reaction Design Pattern

Are all examples of **Concurrency Design Patterns**


---

#### Architectural Design Patterns

---

Architectural design patterns are utilized to implement architectural best practices. 

- MVP Design Pattern (Model-view-presenter)
- MVC Design Pattern (Model-view-controller)
- MVVM Design Pattern (Model-View-ViewModel)

Are all examples of **Architectural Design Patterns*.







---

### Design Pattern Examples

---

A design pattern, each one, is representative of a specific type of solution to a specific type of problem. The best design pattern is never universal. In order to become the best software engineers we can become we need to to learn when a given design pattern should be used. We need to learn which design pattern is best from a contextual vantage point. 

Utilizing a design pattern for a given problem that is not the proper design pattern could not only not be helpful, but could lead to hurting us and our application goals. 

---

### Constructor Pattern

---

In classical object oriented software languages, the constructor is one of the first special functions we learn about. It's the function we use to initialize an object with some set of default property values.


How do we create an object in JavaScript, what are some of the most common ways?

```js
let obj = {}
```

```js
let obj = Object.create(Object.prototype)
```

```js
let obj = new Object();
```

Once we've created our object, there are four ways (since ES3) to actually go about adding properties to our newly created js object.

**Dot Notation**
```js
obj.key = 'value'
```

**Bracket Notation**
```js
obj['key'] = 'value'
```

**Object.definePropeties notation**
```js
Object.defineProperties(obj, {
   'keyOne': { value: 'one', writable: true },
   'keyTwo': { value: 'two', writable: false },
})
```

The curly brackets notation is the most popular way to create objects in JavaScript. The dot notation or square brackets is the most popular way to define properties and set values for those properties.

---

As we talked about earlier, JS does not actually support traditional object oriented classes. However, we do have the `new` keyword in JavaScript. We are able to support constructors in javascript via the `new` keyword. 

We can use a function as a constructor, ultimately initializing an object with properties and passing in values for that objects initial property values using `new`.

```js
function Person(name, email, admin) {
   this.name = name
   this.email = email
   this.admin = admin

   this.isAdmin = () => this.admin === true
   this.isNotAdmin = () => this.admin === false
}


let tim = new Person('Tim', 'tim@gmail.com', false)
let sarah = new Person('Sarah', 'sarah@gmail.com', true)

tim.isAdmin() // false
tim.isNotAdmin() // true

sarah.isAdmin() // true
sarah.isNotAdmin() // false
```

Are we able to improve this syntax? Do we really want to define the functions that an object will have within its constructor? We can also tap into the objects `prototype` to add methods onto the object. Check out this syntax.

```js
function Person(name, email, admin) {
   this.name = name
   this.email = email
   this.admin = admin
}

Person.prototype.isAdmin = function () {
   return this.admin === true
}

Person.prototype.isNotAdmin = function () {
   return this.admin === false
}

let tim = new Person('Tim', 'tim@gmail.com', false)
let sarah = new Person('Sarah', 'sarah@gmail.com', true)

tim.isAdmin() // false
tim.isNotAdmin() // true

sarah.isAdmin() // true
sarah.isNotAdmin() // false
```


---

### Module Design Pattern

---

JavaScript never ceases to amaze when it comes to peculiar things it is capable of achieving. Yes, sometimes these peculiarities are confusing - however this is also comes with the ability to implement some pretty dang powerful patterns. 

One of these weird things JavaScript is capable of compared to other languages is its ability to support access to modifiers.


Before we dive into the module pattern, let's first dive into closure's within JavaScript. Understanding a **closure** is pivotal to really understanding some of the most powerful patterns available to us within JavaScript.

---

#### JavaScript Closures

---

A **closure** is a function with access to the parent scope, even after the parent function has closed. **Closures** assist us in mimicking the behavior of access modifiers through scoping. 

Let's learn via an example.

```js
let Countable = (function () {
   let count = 0

   return function () {
      return count++
   }
})()


console.log(Countable()) // 1
console.log(Countable()) // 2
console.log(Countable()) // 3
```

In this example, we're using **IIFE** - aka an Immediately invoked function expression. 

Every time we call countable, the function it is tied to immediately executes. We're able to do this thanks to the power of functions being first-class citizens in JS.

When this function is called, we actually return another nested function. Since we are not able to access the `count` variable from outside of Countable - we have, through the power of a design pattern, made it a `private` member of the Countable object.

`count` is private. 

---

Via the power of closures, we're able to create objects with private and public parts. These are called **modules** and are extremely useful whenever we need the ability to hide the behavior of certain sub-parts of an object. We're able to _modify_ which behaviors are publicly exposed and which parts are private and **NOT** publicly exposed.

Here's another example:

```js

const Collection = (function() {
   
   // items is a private property
   let items = [];
    
   // everything returned engulfed public properties and methods
   return {
      add: function (item) {
         items.push(item)
      },
      
      remove: function (item) {
         let index = items.indexOf(item)
 
         if (index >= 0) items.splice(index, 1)
      },

      all: function () {
          return JSON.parse(JSON.stringify(items))
      }
   }
})()


Collection.add('Tim')
Collection.add('Sarah')
Collection.add('Raphael')
console.log(Collection.all()) // ['Tim', 'Sarah', 'Raphael']

Collection.remove('Sarah')
console.log(Collection.all()) // ['Tim', 'Raphael']
```

This pattern allows us to introduce a clear partition between private and public parts of an object. This concept is familiar to developers who have that classical object-oriented background experience.


That being said, this doesn't make everything as perfectly complete as we'd like. 

> _What if you want to change the visibility of a member?_

You'd be required to change the code, modifying it in all places where you've used that member because of the _weird_ or different set up we need to setup in order to implement the **module design pattern**


Changing a private part to a public part or vice-versa requires you to change several internal dependency points within your code. 


---

### Revealing Module Design Pattern

---

Let's improve the module design pattern we illustrated above. Our main differential is that we're going to write the entire object logic within the private scope of the module and then expose parts in which we want exposed as public by returning an anonymous object. 

We can also change the naming of private members when mapping private members to their corresponding public members. 


```js
const Collection = (function () {
   /* Private Members */
   let items = []
   
   function all () { 
      return JSON.parse(JSON.stringify(items)) 
   }

   function add (item) { 
      items.push(item) 
   }   

   function remove (item) {
     let index = items.indexOf(item)
     if (index >= 0) items.splice(index, 1)
   }
   
   /* Public Members */
   return {
      addItem: add,
      allItems: all,
      removeItem: remove,
   }
})()

Collection.addItem('Tim')
Collection.addItem('Sam')
Collection.addItem('Ben')

console.log(Collection.allItems()) // ['Tim', 'Sam', 'Ben']

Collection.remove('Sam')
console.log(Collection.allItems()) // ['Tim', 'Ben']
```


This example, shown directly above, is what's known as the revealing module pattern. It is one of at least 3 differing ways in which we're able to implement the module pattern.

What's the difference between the revealing module pattern and all of the other variations of the module design pattern?

The differences are primarily based on how public members are referenced. As the outcome, the **revealing module design pattern** is much easier to use and modify. 

With that being said, this design pattern may be  fragile in certain contexts (remember that no single design pattern is universally the best fit). 

Here's a couple of problematic situations to consider when asking whether you should utilize the **Revealing module pattern**.

---

- 1. A private function is referring to a public function. In this scenario we cannot override the public function using this design pattern. When we attempt to override it, we'll introduce a bug to our software due to the private function continuing to refer to the private implementation of the function.

- 2. We shouldn't use this design pattern if we have a public member pointing to a private variable, and then proceed to try to override the public member from outside the module. In this scenario the other functions would still refer to the private value of the variable, introducing a bug into our software.

---

### Singleton Design Pattern

---

The singleton design pattern is used in situations where we need exactly one instance of a class. The Singleton design pattern is in the creation design pattern category. 

Imagine, for example, we need to have an object which contains some configuration settings for our applications defined before our runtime even begins. In these scenario, is is not necessary to create a whole new object every time we need this configuration object. The configuration settings defined by the user need to be loaded into an object one time so our JS runtime can access the config settings, but we don't need to re-create this object every single time we try to access the config settings.


```js
const Singleton = (function () {
   // Private config 
   let config;

   function initializedConfigurationSettings (values) {
     this.random = Mathod.random()
     values = values || {}
     this.number = values.number || 5
     this.size = values.size || 10
   } 

  return {
     getConfig: function (values) {
       // we initialize the singleton value only once
       if (config === undefined) {
         config = new initializedConfigurationSettings(values)
       }

       return config
     }
  }
}();

const ConfigurationSettings = singleton.getConfig({ app: 'HelloWorld', environment: 'local' })

console.log(ConfigurationSettings) // { app: 'HelloWorld', environment: 'local' }

ConfigurationSettings.getConfig({ "number": 8 })
// same randomDecimalValue as in the first config - aka we've proven it's the same object
```

In this example, you can see that we generate a random number. If you were to use this code - that randomly generated number would be the same after the first call to `singleton.getConfig`. This is our way of proving that the singleton object returns the same object each time. We only create the object one time and then return the same configuration object each time after that.


---

### Observer Design Pattern

---


The observer design pattern is in my opinion one of the most powerful design patterns out there - especially within JavaScript. 

The observer design pattern is a **Behavioral Design Pattern**. We can this design pattern to improve the communication between contrasting parts of a software application. 


This design pattern does have several variants when it comes to its implementation, but its most basic form has tow main parts.


- **Part One:** Subject
- **Part Two:** Observers


A subject is responsible for handling all of the operations regarding a certain topic. Observers _subscribe_ to this subject. 

An observer can **subscribe** and **unsubscribe** from a topic.

---

Imagine that we have two types of objects:

A customer.

A store.

The customer is interested in a particular brand of product (Ex: iPhone) which should become available in the store very soon.

Having the customer visit the store every day and check product availability is resource intensive. Instead, the customer can subscribe to the iPhone topic provided by the store. 

**Solution:**

The object that has some sort of interesting state is the _subject_. Since it is also going to notify other object about the changes to its state we'll _also_ call it the _publisher_. 

All other objects, in our case customers, are going to be the _subscribers_. 


```js

let publisher = {}

(function (container) {
   // represents a unique subscription id to a topic
   let id = 0 

   container.subscribe = function (topic, callback) {
      if (!(topic in container)) container[topic] = []

      container[topic].push({ id: id++, callback: callback })

      return id
   }

   container.unsubscribe = function (topic, id) {
     let subscribers = []

     for (let subscriber of container[topic]) 
        if (subscriber.id !== id) 
           subscribers.push(subscriber)
     
     container[topic] = subscribers
   }


   container.publish = function (topic, data) {
      for (let subscriber of container[topic]) 
          subscriber.callback(data)
   }
})(publisher)


let subscription_1 = publisher.subscribe('mouseClicked', function (data) {
    console.log(
        "Sam's callback for mouse click: ", 
        "Event Data: ",
        JSON.stringify(data)
    )
})


let subscription_2 = publisher.subscribe('mouseHovered', function (data) { 
    console.log(
        "Sam's callback for mouse hovered: ", 
        "Event Data: ",
        JSON.stringify(data)
    ) 
})



let subscription_3 = publisher.subscribe('mouseClicked', function (data) {
    console.log(
       "Sarah's callback function for mouse click: ", 
       "Event Data: ",
       JSON.stringify(data)
    )
})


publisher.publish('mouseClicked', { data: 'data1' })
publisher.publish('mouseHovered', { data: 'data2' })


// unsubsribe from an event 

publisher.unsubcribe('mouseClicked', subscription_3)

publisher.publish('mouseClicked', { data: 'data1' })
publisher.publish('mouseHovered', { data: 'data2' })
```

The observer design pattern is extremely useful in situations where we need to perform multiple operations based on a single event that is being fired. 

**Example:**

Imagine a scenario where we need to make multiple AJAX calls to an API and then we need to go a step further and perform other AJAX calls depending on our result from the data returned from our initial set of calls.

You would have to nest the AJAX calls one within the other, possibly entering into a situation known as callback hell. Using the publisher/subscriber pattern is a much more elegant solution.

**Downsides of the Observer Design Pattern**
- Difficult testing of various parts of our system.


---

### Prototype Design Pattern

---

As noted throughout the entirety of this article, JS does **NOT** support classes in the classical OOP native understanding.

Due to this fact, inheritance between objects is implemented using prototype-based programming. This allows us the ability to create objects which can serve as a **prototype** for other objects being created in JavaScript. The prototype object is used as a blueprint for each object the constructor creates.

Let's show a simple implementation of this prototype pattern implementation in JS. 

```js
let PersonPrototype = {
   hi: function () { console.log(`Hello, my name is ${this.name}, and I'm ${this.age}.`) },

   bye: function () { console.log(`I'm ${this.name} and I'm saying bye now!`) }
}


function Person (name, age) {
    age = age || 26
    name = name || "John Doe"


    function constructorFunction(name, age) {
        this.age = age
        this.name = name
    }

    constructorFunction.prototype = PersonPrototype

    let obj = new constructorFunction(name, age)
    return obj
}

let person1 = Person()
let person2 = Person("Tim", 38)


person1.hi() // "hello, my name is John Doe and I'm 26
person2.hi() // "hello, my name is Tim and I'm 38

```

Prototyping is how inheritance works in JS and this is just a simple example of its implementation. 


---

### Command Design Pattern

---

The command design pattern is something we can use in cases when we want to decouple objects executing the commands from objects issuing the commands that we want to execute. 

**Example:**

Imagine a situation where our application is using a large amount of API calls for given application services. These API services change. 

Understanding this weird oddity in the challenge to implementing a solid coding solution for this problem we could use the Command Design Pattern.

We'd want to implement an abstraction layer. This abstraction layer would separate the objects calling an API service from the objects which are telling them _when_ to call the API service. This implementation would avoid the need to modify our code in all of the places where we have a need to call the service. Rather we'd have to change the objects that are making the calls themselves - which is saying we only need to make the change in one place instead of multiple places.

A huge point when it comes to design patterns is that we must become accustomed to understanding the trade offs we are making when deciding to utilize any given design pattern. 

Are we adding un-needed abstraction layers or are we solving a dependency erosion issue that calls for abstraction layer to solve properly? 

```js
let invoker = {
   add: function (x, y) { return x + y },
   subtract: (x, y) { return x - y },
}

let manager = {
   execute: function (name, args) {
      if (name in invoker) { 
          return invoker[name].apply(invoker, [].slice.call(arguments, 1))
      }

      return false
   }
}

console.log(manager.execute("add", 3, 5)) // 8
console.log(manager.execute("subtract", 5, 3)) // 2
```


---

### Facade Design Pattern 

---

What's the Facade design pattern? Using this design pattern we are able to create an abstraction layer between what is shown publicly and what is implemented behind the curtain. This design pattern is powerful to increase readability. 

A great example of this pattern would be selectors from DOM manipulation libraries such as jQuery, Dojo, or D3. You might have noticed using these libraries that they have very powerful selector features; you can write in complex queries such as:

```js
jQuery(".parent .child div.span")
```

In this example, the selection feature syntax is simplified quite a bit. Even though it seems simple on the surface, the logic behind the scene being implemented is much more complex. Under the hood we're doing a lot, but the externally facing API end users (in this case developers being the end users) is simplified. 

We love simplifying :) 


---

### Next Steps 

---

Design patterns are one of the most powerful tools in a software engineers tool belt - if you're looking to turn yourself into a senior JavaScript developer there are a plentiful amount of these design patterns you should be aware of.

Knowing how, when, where, and the trade-offs of implementing design patterns are all characteristics that the JavaScript engineers that lead teams should understand very well.

[Refactoring Guru](https://refactoring.guru) is a great resource to utilize when it comes to understanding these design patterns. 

We could display a hundred more design principle examples in this article, but the truth is one article can't encompass all of the available design principles out their at your disposable. 

I highly recommend making it a goal to learn two new design principle per week. After a year, you'll have 104 design principles at your disposable. You'll be multiple times more valuable as a software engineer to any team and organization. 

For those interested to take the deep dive now, I recommend the Gang of Four book.

**Design Patterns: Elements of reusable object-oriented software.**

---

<a target="_blank"  href="https://www.amazon.com/gp/offer-listing/0201633612/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0201633612&linkCode=am2&tag=ccs0cc-20&linkId=07842ca29d36da06ae2d26a3276a26a5"><img border="0" src="//ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=0201633612&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ccs0cc-20" ></a>

---

Thanks for reading and feel free to follow Clean Code Studio for more! 

[Clean Code Studio](https://cleancode.studio)
[Java Script Design Patterns](https://cleancode.studio/design-patterns)
[Clean Code](https://cleancode.studio/clean-code)
[JavaScript Algorithm Examples](https://cleancode.studio/algorithms)

[JavaScript Data Structures](https://cleancode.studio/data-structures)
