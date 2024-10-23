# Simple-Sub with Extensible Records

Adapted from [Rodrigo Marques' implementation](https://github.com/marques-rodrigo/simple-sub-records) of algebraic subtyping with extensible records (ML Workshop 2022). 

## Compiling & Running
- This project compiles with GHC 9.6.6.
- Run `stack build` to compile
- Run `stack exec` to start a REPL which takes in user-supplied terms (e.g. `succ`) and produces types. We add `extend term with {x = term}` to the original syntax.

