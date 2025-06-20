# Functional Programming Crash Course (Inspired by HtDP + SICP)

A 7–14 day crash course to teach recursion, abstraction, higher-order functions, and program design — without committing to Racket or Scheme.


## Week 1: Core Concepts of Functional Thinking

### Day 1 – Pure Functions & Function Composition
- [ ] Write 3 small **pure functions** (no side effects).
- [ ] Chain `.map()`, `.filter()`, `.reduce()` or `.fold()` to solve:
  - [ ] Sum of squares of even numbers
  - [ ] Capitalize and sort strings
- [ ] Build a `compose(f, g)` function to chain functions together


### Day 2 – Recursion Deep Dive
- [ ] Write recursive:
  - [ ] Factorial
  - [ ] Fibonacci
  - [ ] List reverse
  - [ ] Nested list sum
- [ ] Explain why recursion is better than iteration in certain contexts


### Day 3 – Higher-Order Functions
- [ ] Write `apply_twice(f, x)` – applies `f(f(x))`
- [ ] Write `make_multiplier(n)` – returns a function that multiplies by `n`
- [ ] Map a function over a list of strings or numbers
- [ ] Implement your own version of `map()` as a function


### Day 4 – Data Abstraction
- [ ] Define a custom data type (e.g. `Point`, `Rectangle`)
- [ ] Write only getters/setters to access the data
- [ ] Enforce a contract: external code should not rely on the structure


### Day 5 – Trees & Recursive Data Structures
- [ ] Define a binary tree type
- [ ] Implement:
  - [ ] Tree sum
  - [ ] Tree depth
  - [ ] `map_tree(f, tree)` – apply function to each value
- [ ] Visualize recursion through a drawing or diagram


### Day 6 – Program Design (HtDP "Design Recipe")
- [ ] Pick a problem (e.g. todo logic, calculator, account sim)
- [ ] Follow the HtDP steps:
  - [ ] Define data
  - [ ] Write examples
  - [ ] Function signatures
  - [ ] Write tests first
  - [ ] Implement incrementally


### Day 7 – Mini Project Day
Choose one:
- [ ] Build a recursive **expression evaluator** (e.g. `(+ (* 2 3) 5)`)
- [ ] Build a **mini file search CLI** using recursion over directories
- [ ] Create a toy **Lisp-like interpreter** using AST + recursion


## Optional Week 2: Advanced Abstractions & Interpreters

### Day 8 – Basic Interpreter (SICP Style)
- [ ] Parse prefix expressions like `(+ 1 (* 2 3))`
- [ ] Convert to AST (Abstract Syntax Tree)
- [ ] Recursively evaluate the AST


### Day 9 – Closures & Environments
- [ ] Write `make_counter()` → returns a closure that increments a count
- [ ] Explain how lexical scoping captures variables
- [ ] In Rust: use `move` closures
- [ ] In Python: use `nonlocal` for mutable closure state


### Day 10 – Simulating State
- [ ] Create a functional counter: return new state on each call
- [ ] Create a mutable counter: internal state updates each time
- [ ] Compare the benefits/drawbacks of each


### Day 11 – Abstract Data Types & Traits
- [ ] Define a generic `Stack<T>` with push/pop
- [ ] Use traits/interfaces for abstraction
- [ ] Write tests and document as if publishing a crate or module


### Day 12–14 – Final Capstone
Choose one:
- [ ] Write a full **Lisp-like interpreter** (basic eval + functions)
- [ ] Build a small **functional query engine** (e.g. filter/sort JSON)
- [ ] Extend your tree/map code into a working **toy database**


## Recommended Readings (Optional)
- [ ]  *The Little Schemer* – chapters 1–4 (teaches recursion playfully)
- [ ]  *SICP (Ch. 1 & 2)* – core ideas of computation, abstraction
- [ ]  *The Rust Book* / Python docs – to fill syntax/practical gaps
- [ ]  Crust of Rust / CS61A videos for HOFs and environments

## Tools (Language-Agnostic)
- Git + GitHub (track and version your work)
- Unit tests (write them early and often)
- Diagrams (draw trees, call stacks, environments)


