# Rust Raw Pointer and Vector Modification Bug
This repository demonstrates a common bug in Rust involving the use of raw pointers and vector modifications.  Modifying a vector's contents via a raw pointer after changing the vector's length can lead to undefined behavior and unexpected crashes.

The `bug.rs` file contains the buggy code, while `bugSolution.rs` shows a corrected version using safer methods. This example highlights the importance of careful memory management when working with raw pointers in Rust.