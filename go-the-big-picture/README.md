# Go: The Big Picture

## About

* Author: Mike Van Sickle
* Provider: Pluralsight

## Course Overview

* Why Go was created
* Programming with GO
* Go's ecosystem

## Why Go?

### Introduction

* Course Outline
  * Why Go?
  * Programming with Go
  * Leveraging the Go Ecosystem

### Why Create Go?

* To solve the challenges of present programming language
  * Efficient compilation
  * Efficient execution
  * Ease of programming
* Python = Ease of programming + efficient compilation
* Java = Efficient execution + efficient compilation
* C++ = Efficient execution

### Guiding Principles

* Simplicity as a core value
  * For loop: No for each
* Commitment to backward compatibility
  * Stable production environment
* Made for concurrent, network enabled application
* Holistic approach to solve common problems

### Language Characteristics

* Strong static type system
  * Variable is defined and simple to understand by the compiler
* C-inspired syntax
* Garbage collected
  * Simplifies go programs
  * Cleans the unused memory efficiently
* Fully compiled
* Rapid compilation
  * Fast compilation
  * Feels like using scripting language
* Single binary output
  * Compiled into a single binary
  * Deployed by a single binary into the container if used Docker
* Cross-platform
  * Compiled into binary for an environment

### Primary Use Cases

* Cloud and network services
    * Microservices
* Command-line interfaces
  * Rapid compilation allows efficient CLI applications
* Cloud infrastructure
  * Docker, K8s, Terraform

### Summary

* Why create Go?
* Language characteristics
* Primary use cases

## Programming with Go

### Introduction

* Language characteristics and evolution
* Demos
  * Hello, world!
  * Web services
  * Command line programs

### Language characteristics and evolution

* Go's Evolution
  * C -> C++ -> Java -> C# | JS | Python
  * C -> Go

### Demo: Hello, World

```golang
go mod init demo

module demo
go 1.19
```

### main.go

```golang
package main

func main(){
    fmt.Println("Hello, World!)
}
```

```bash
go run .
```
