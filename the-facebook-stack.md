# The Facebook stack

React is one piece of the puzzle.

When a decade ago Facebook decided to rethink their entire web stack and infrastructure[^1] -- they threw out everything and replaced:

- imperative programming with functional and reactive programming
- the DOM with the shadow DOM
- HTML, CSS and Javascript with web components
- Client-server architecture with Event-driven architecture
- REST APIs with GraphQL APIs
- Don't Repeat Yourself (DRY) with the **Single Responsability Principle (SRP)**

With the new stack:

- One *declares* how the app will work instead of writing it (React).
- The database is *designed on the front-end*, component-by-component, without worrying about the whole picture, normalization and performance. (GraphQL)
- There is *one single call to a server per page* instead of REST API endpoints and CRUD operations. (Relay)
- Presentation and styling goes with Design Systems insetad of hand-written HTML, CSS and Javascript code.

Making one's mind to embrace the whole new stack is not a trivial task. 

Perhaps the process should start with learning functional and reactive programming. 

Then try React in a classic enveironment:  MVC / REST / CRUD / Client-server architecture. 

In a next project embrace GraphQL with a non-Relay server like Apollo.

As a last step adhere to the complete Facebook stack with Relay.

Better follow the creators. Reinventing the wheel is always costly and painful.

## Footnotes
[^1]: [We're gonna program like it's 1999](http://metamn.io/react/were-gonna-program-like-its-1999/)