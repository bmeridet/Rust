# LoxVM – A Bytecode Virtual Machine in Rust

LoxVM is an educational implementation of a **bytecode virtual machine** for the
[Lox programming language](http://craftinginterpreters.com/) written entirely in **Rust**.

The goal of this project is to follow the *Crafting Interpreters* book’s second half
(the “clox” VM) while taking advantage of Rust’s:
- strong type system,
- safe memory management,
- explicit error handling, and
- modern tooling (`cargo`, `clippy`, `rustfmt`, etc.).

---

## ✨ Features (Planned / Implemented)
- [ ] **Lexer / Scanner** for the Lox source code
- [ ] **Parser** that generates bytecode instructions
- [ ] **Stack-based VM** executing bytecode
- [ ] Support for **globals, locals, closures**
- [ ] **Garbage collector** for managing Lox objects
- [ ] **REPL** for interactive use
- [ ] **Bytecode disassembler** for debugging

---
