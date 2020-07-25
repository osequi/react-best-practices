# react-best-practices
React Best Practices

- Created with https://obsidian.md/
- See [[react-best-practices]]

# Introduction 1

React is the most popular web framework today[^1].  

Created by Facebook in 2013 the ecosystem grew mature in 2019. That year the facebook.com redesign and rewrite stack of choice became React, GraphQL and Relay[^2].

Strong support from a major player drove the attention of web and Javascript developers already familiar with another frameworks.

Devs flocking to React often found the learning curve steep[^3]. due to the fact React brings more novelty to the table than other emerging frameworks like Vue, Svelte. 

It's a new programming and information architecture paradigm unseen before on the web.

Learning React means learning type-safety; functional and reactive programming; data-driven applications; graph databases and event-driven architectures.

And as they say, forgetting apriori knowledge about web development may greatly help along the process.

## Footnotes
[^1]: [The State of JavaScript Survey 2019](https://2019.stateofjs.com/front-end-frameworks/)
[^2]: [Building the New facebook.com with React, GraphQL and Relay](https://developers.facebook.com/videos/2019/building-the-new-facebookcom-with-react-graphql-and-relay/)
[^3]: [How to learn React.js in 2020](https://www.robinwieruch.de/learn-react-js)
[^4]: [A Big Picture](http://metamn.io/react/a-big-picture/)

# Audience

React is suitable for everyone because it's a completely novel approach to web development.

If one already knows HTML, CSS it might help but doesn't offer an outsanding advantage. Components and design systems hide these abstractions and incorporate the necessary knowledge to build web applications. 

Programming experience helps only if it's functional. In React no one writes complex algorithms; instead manipulates the data flow using functional programming concepts.

The knowledge of older paradigms like MVC, REST and CRUD doesn't helps either. The React ecosystem -- GraphQL and Relay -- sports concepts unseen previously in web frameworks.

When learning React one will find out: 

1. React is not just another web framework.
2. React is functional and reactive.
3. It comes together with am ecosystem, a complete stack from UI design to back-end servers.
4. React apps are best written using Facebook's original guidelines.

# The Facebook stack

React is one piece of the puzzle.

Facebook decided a decade ago to rethink their approach to web programming and infrastructure[^1] . They threw out everything old and replaced:

- Imperative programming with functional and reactive programming
- DOM with the shadow DOM
- HTML, CSS and Javascript with web components and design systems
- Client-server architecture with Event-driven architecture
- REST APIs with GraphQL APIs
- Don't Repeat Yourself (DRY) with the **Single Responsability Principle (SRP)**

With the new stack:

- Devs *declare* the app functionality instead of writing sophisticated algorithms.
- Devs *declare* their data needs on the front-end instead of waiting for from the back-end.
- Devs *declare* the app style using design systems vs. writing HTML and CSS by hand.
- The ecosystem, GraphQL and Relay, handles all else in the background. Collects all data needs of a page into a single call to the backend -- for example.

Making one's mind to embrace this new stack is not always trivial. Learning React perhaps should follow the small steps:

1. Start with learning functional and reactive programming. 
2. Read and understand Thinking in React.
3. Try React in a classic REST API environment.
4. Move to GraphQL with a non-Relay server like Apollo.
5. Swicth to the complete Facebook stack with Relay.
6. Understand type safety; data-driven applications; graph databases and event-driven architectures.

With plenty of will, time and courage an exciting new ecosystem will unfold. 

Where all parts are important, made to fit and work together. 

## Footnotes
[^1]: [We're gonna program like it's 1999](http://metamn.io/react/were-gonna-program-like-its-1999/)

# The Facebook way

React is an un-opinionated framework. Apps written in React vary in coding style from developer to developer, company to company.

As always, is best to follow the creators.

Facebook, the creator of React, published Thinking in React[^1] -- a set of guidelines "to think about apps as you build them" or  "the thought process of building with React".

Omitting these guidelines is reinventing the wheel. Chances are slim to come up with a better solution. Unless one masters better resources than Facebook.

Practicing Thinking in React surfaces, after a while, the following advantages: 

- Decision making becomes easy. 
- Code written by a team looks like code written by a single person.
- Re-usable components and business logic grows from project to project becoming wealth.

What is Thinking in React, then?

## Footnotes
[^1]: [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)




