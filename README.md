# The Currents of Concurrency: reasoning with async Rust

This presentation was given at RustLab 2024.

## Abstract

Reasoning through concurrent systems has always been a challenging
task. Poor code can be riddled with race conditions, non-terminating
cases and other complex concurrency bugs; and even well-written code
can be hard to understand. Async programming is an innovative
concurrent programming model that rises to this challenge. In this
talk, we'll explore reasoning with async Rust. We'll be introduced to
its fundamental building blocks, such as `async`, `await`, `join` and
`select`, and learn how to predict the behavior of code written with
them. We'll build on these to simplify more complex concurrency
puzzlers. Finally, we'll explore different approaches to handling
concurrent state and see how they compare.
