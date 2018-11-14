# JavaScript interview questions

> You need to see the big picture. Ask about architechture and paradigms.

### 1. Can you name two programming paradigms important for JavaScript app developers?

JavaScript is a multi-paradigm langugage, supporting **imperative/procedural** programming
along with **OOP** (Object-Oriented Programming) and **functional programming**.
JavaScript supports OOP with **prototypal inheritance**

**Good to hear**
* Prototypal inheritance (also: prototypes, OLOO).
* Functional programming (also: closures, first class functions, lambdas).

**Red flags:**
* No clue what a paradigm is, no mention of prototypal oo or functional programming.

**Learn More:**

[The Two Pillars of JavaScript Part 1](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3)— Prototypal OO.

[The Two Pillars of JavaScript Part 2](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4) — Functional Programming.

---
### 2. What is functional programming?

Functional programming produces programs by composing mathematical functions and avoids
shared state & mutable data.

Lisp (specified in 1958) was among the first languages to support functional programming, and was heavily inspired by lambda calculus. Lisp and many Lisp family languages are still in common use today.

Functional programming is an essential concept in JavaScript (one of the two pillar of JavaScript).
Several common functional utilites were added to JavaScript since ES5.

**Good to hear**
* Pure functions / function purity.
* Avoid side-effects.
* Simple function composition.
* Example of functional languages: Lisp, ML, Haskell, Erlang, Clojure, Elm, F Sharp, OCaml, etc...
* Mention of features that support FP: first-class function, higher order functions, functions as arguments / values.

**Red flags:**
* No mention of pure functions / avoiding side-effects.
* Unable to provide examples of functional programming languages.
* Unable to identify the features of JavaScript that enable FP.

**Learn More:**
* [The Two Pillars of JavaScript Part 2.](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4)
* [The Dao of Immutability.](https://medium.com/javascript-scene/the-dao-of-immutability-9f91a70c88cd)
* [Composing Software.](https://medium.com/javascript-scene/composing-software-an-introduction-27b72500d6ea)
* [The Haskell School of Music.](http://haskell.cs.yale.edu/wp-content/uploads/2015/03/HSoM.pdf)
