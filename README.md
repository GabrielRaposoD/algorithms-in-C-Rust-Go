# Algorithms in C, Rust, and Go

This repository contains implementations of various fundamental data structures and algorithms in three programming languages: C, Rust, and Go. The goal is to understand and compare the implementation and performance of these algorithms across different languages.

## Table of Contents

- [Introduction](#introduction)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
- [Development Environment Setup](#development-environment-setup)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Testing](#testing)
- [Documentation](#documentation)
- [Performance Comparison](#performance-comparison)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to implement common data structures such as one-way lists, two-way lists, graphs, and binary trees in C, Rust, and Go. By comparing these implementations, we hope to gain insights into the strengths and weaknesses of each language regarding algorithm implementation and performance.

## Data Structures and Algorithms

### One-way Lists (Singly Linked Lists)

- **Operations**: Insertion, Deletion, Traversal, Searching

### Two-way Lists (Doubly Linked Lists)

- **Operations**: Insertion, Deletion, Traversal, Searching, Reverse Traversal

### Graphs

- **Types**: Directed, Undirected
- **Representation**: Adjacency List, Adjacency Matrix
- **Algorithms**: Depth-First Search (DFS), Breadth-First Search (BFS), Dijkstra's, Prim's, Kruskal's

### Binary Trees

- **Types**: Binary Search Tree (BST), AVL Tree, Red-Black Tree
- **Operations**: Insertion, Deletion, Traversal (In-order, Pre-order, Post-order), Searching

## Development Environment Setup

### C

- Ensure you have a C compiler installed (e.g., GCC).
- Use `make` for building and running tests.

### Rust

- Install Rust from [rust-lang.org](https://www.rust-lang.org/).
- Use `cargo` for building and running tests.

### Go

- Install Go from [golang.org](https://golang.org/).
- Use `go build` and `go test` for building and running tests.

## Folder Structure

```
algorithms-in-C-Rust-Go/
├── README.md
├── LICENSE
├── C/
│   ├── linked_list/
│   │   ├── main.c
│   │   ├── linked_list.c
│   │   ├── linked_list.h
│   │   └── tests/
│   │       └── linked_list_tests.c
│   ├── doubly_linked_list/
│   │   ├── main.c
│   │   ├── doubly_linked_list.c
│   │   ├── doubly_linked_list.h
│   │   └── tests/
│   │       └── doubly_linked_list_tests.c
│   ├── graph/
│   │   ├── main.c
│   │   ├── graph.c
│   │   ├── graph.h
│   │   └── tests/
│   │       └── graph_tests.c
│   └── binary_tree/
│       ├── main.c
│       ├── binary_tree.c
│       ├── binary_tree.h
│       └── tests/
│           └── binary_tree_tests.c
├── Rust/
│   ├── linked_list/
│   │   ├── src/
│   │   │   ├── main.rs
│   │   │   ├── linked_list.rs
│   │   │   └── lib.rs
│   │   └── tests/
│   │       └── linked_list_tests.rs
│   ├── doubly_linked_list/
│   │   ├── src/
│   │   │   ├── main.rs
│   │   │   ├── doubly_linked_list.rs
│   │   │   └── lib.rs
│   │   └── tests/
│   │       └── doubly_linked_list_tests.rs
│   ├── graph/
│   │   ├── src/
│   │   │   ├── main.rs
│   │   │   ├── graph.rs
│   │   │   └── lib.rs
│   │   └── tests/
│   │       └── graph_tests.rs
│   └── binary_tree/
│       ├── src/
│       │   ├── main.rs
│       │   ├── binary_tree.rs
│       │   └── lib.rs
│       └── tests/
│           └── binary_tree_tests.rs
├── Go/
│   ├── linked_list/
│   │   ├── main.go
│   │   ├── linked_list.go
│   │   └── linked_list_test.go
│   ├── doubly_linked_list/
│   │   ├── main.go
│   │   ├── doubly_linked_list.go
│   │   └── doubly_linked_list_test.go
│   ├── graph/
│   │   ├── main.go
│   │   ├── graph.go
│   │   └── graph_test.go
│   └── binary_tree/
│       ├── main.go
│       ├── binary_tree.go
│       └── binary_tree_test.go
└── docs/
    ├── linked_list.md
    ├── doubly_linked_list.md
    ├── graph.md
    └── binary_tree.md
```

## Usage

### C

Navigate to the desired data structure directory and use `make` to build and run the program.

```sh
cd C/linked_list
make
./linked_list
```

### Rust

Navigate to the desired data structure directory and use `cargo` to build and run the program.

```sh
cd Rust/linked_list
cargo build
cargo run
```

### Go

Navigate to the desired data structure directory and use `go run` to run the program.

```sh
cd Go/linked_list
go run main.go
```

## Testing

### C

Navigate to the `tests/` directory and run the test files.

```sh
cd C/linked_list/tests
make
./linked_list_tests
```

### Rust

Use `cargo test` to run the tests.

```sh
cd Rust/linked_list
cargo test
```

### Go

Use `go test` to run the tests.

```sh
cd Go/linked_list
go test
```

## Documentation

Detailed documentation for each data structure and its implementation can be found in the `docs/` directory.

## Performance Comparison

Performance benchmarks and comparisons will be documented and available in the `docs/performance.md` file.

---

This README provides a comprehensive overview of the project, guiding users through setup, usage, testing, and contribution.
