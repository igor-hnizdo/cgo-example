# CGO Example

[![Build Status](https://travis-ci.org/cpliakas/cgo-example.svg?branch=master)](https://travis-ci.org/cpliakas/cgo-example)

A simple CGO application that prints "Hello, world!" in Go reading the data
from a library in C.

## Installation

Assuming a [correctly configured](https://golang.org/doc/install) Go
toolchain:

```shell
git clone https://github.com/igor-hnizdo/cgo-example
cd cgo-example
go build
```

## Usage

Run `cgo-example` on the command line, and it should return `Hello, world!`.

## How Does It Work?

**TODO**

## Should You Be Doing This?

Maybe, but probably not. Relevant articles on this topic are listed below:

* [The Cost and Complexity of Cgo](https://www.cockroachlabs.com/blog/the-cost-and-complexity-of-cgo/)
* [cgo is not Go](https://dave.cheney.net/2016/01/18/cgo-is-not-go)
