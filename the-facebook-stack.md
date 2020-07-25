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