<div align="center">

## Tinygrad-rs
#### An attempt to write better rust, code, and an ML framework.

[![Rust](https://img.shields.io/badge/Rust-orange.svg?style=for-the-badge&logoColor=white&logo=rust)][rust]
[![Tinygrad](https://img.shields.io/badge/Tinygrad-3776AB.svg?style=for-the-badge&logoColor=white)][tinygrad]
[![Tinycorp](https://img.shields.io/badge/Tiny_Corp-white.svg?style=for-the-badge&logoColor=white)][tinycorp]

[rust]: https://www.rust-lang.org/
[tinygrad]: https://github.com/geohot/tinygrad
[tinycorp]: https://tinygrad.org/

</div>

## ⇁  Welcome
This is tinygrad-rs. An attempt to improve tinygrad without contritbuting to the main repository. I am currently learning rust, and ML so bear with me if the code is not great. If you want to improve my code feel free to send in a PR.

## ⇁  Current status
This project will be worked on from time to time. If I find the time outside of work/school.

## ⇁  Contribute
If you want to help me with this project. Feel free to fork the repo and send in a PR. Look into the [todo.txt](./docs/todo.txt) file for a list of things that needs to be done. I will also try to keep this repo up to the highest standards.

### ⇁  File structure
Below is the idea of how the file structure will set up. It will mirror that of Tinygrad so if you want to add one of these files feel free to send in a PR. 

```
├── README.md
├── cargo.toml
├── tests - Tests for tinygrad-rs
├── tinygrad - Core tinygrad-rs
│   ├─ src
│   │  ├── ast.rs - Definitions for representing abstract syntax trees
│   │  ├── graph.rs - Creating visual graphs of the Tensors dependencies.
│   │  ├── helpers.rs - Various helper functions
│   │  ├── lazy.rs - Things that deal with the lazy evaluation of Tensors
│   │  ├── llops - Definitions for low-level operations 
│   │  ├── mlops.rs - Mid-level operations 
│   │  ├── nn - Neural network-level things
│   │  ├── ops.rs - Basic definitions for Tensor operations 
│   │  ├── shape - Things that deal with Tensor shapes
│   │  └── tensor.rs - Main Tensor class
│   └── cargo.toml
```

Note that I will probably change the overall stucture of the repo. The idea was to have a simple rewrite, but if a file or folder requires it we will change the overall sturcture
