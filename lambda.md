http://www.cs.cmu.edu/~rwh/pfpl/supplements/ulc.pdf

Q: I think Im confused because when you say lambda term that does not mean that every or that x will have a symbol lambda attached to it, you are simply saying that x is a lambda term?

A: In λ-calculus, "λ-term" is just a way of classifying valid expressions in the system. Since variables are defined as valid starting points for building λ-terms, x qualifies as a λ-term even though it doesn't contain the λ symbol.

Think of it this way:

- The λ-symbol appears explicitly in function definitions (abstractions), such as λx.x, but not in variables or applications.
- Variables are included in the system because we need "atomic" symbols to build more complex terms, like functions and applications.

Expressions of the λ-calculus are called λ-terms. They have one of three forms:
1. A variable, x.
2. An application, ap(M1 ; M2), of λ-term M1 to another λ-term M2.
3. An abstraction, λ(x.M ), of a variable x within the λ-term M

