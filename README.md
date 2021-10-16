# lox.rs

Yet another implementation of the Lox bytecode VM from [Crafting Interpreters](https://craftinginterpreters.com/).

This one is written in Rust instead of C because CMake (and C for that matter) is a pain, and Rust's performance should be pretty equivalent.

The goal is to learn how to do the thing by following along with the book, so the end result should be a program that's nearly identical to the reference C implementation in terms of memory representation and runtime behavior, but I will be using Rust idioms as much as possible within the bounds of that constraint.
