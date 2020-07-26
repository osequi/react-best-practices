# Functional and reactive programming

React follows the functional reactive programming paradigm[^1]. That’s a shift from the old proactive, imperative approach.

Both paradigms solve the same problem in different ways: build *modular*, *interactive* applications.

The old way implemented modularity through tight-coupling, and interaction synchronously. The new way implements modularity with loose-coupling, and interaction asynchronously.

To clear the picture let's abstract modularity and interaction to *composition* and *coupling*.

Composition is about how the components of the system can add up to form a whole, while coupling is about how they communicate with each other.

## Composition

Composing up a system from smaller parts is best possible when the underlying components behave predictably:

1. They have clear and stable interfaces — input parameters and return values — to ease combinations.
2. They process input parameters into return values in a clean way:
	1. Avoid modification of input parameters.
	2. Avoid adding external information. Input parameters are enough to produce the return value. 
	3. Avoid addeing external operations. The algorithm does the transformation and that's all.


## Footnotes
[^1]: [An Introduction to Functional Reactive Programming](https://blog.danlew.net/2017/07/27/an-introduction-to-functional-reactive-programming/)

## Resources
1. [The original article](http://metamn.io/react/the-reactive-fuctional-nature-of-react/)