# go-libs

This repo contains the list of good-to-use Golang libraries.


## Error Handling

* A Go (golang) package for representing a list of errors as a single error. **Not relevant anymore.**
  https://github.com/hashicorp/go-multierror


* Simple error handling primitives. **INACTIVE**
  https://github.com/pkg/errors

## Application lifecycle

* Graceful shutdown using `graterm` library.
  https://github.com/skovtunenko/graterm


* Wiring of application components using Wire
  https://github.com/google/wire

## Scripting

* The Common Expression Language (CEL) is a non-Turing complete language designed for simplicity, speed, safety, and portability.
  https://github.com/google/cel-go

## Goroutine management

* Package **errgroup** provides synchronization, error propagation, and Context cancelation for groups of goroutines working on subtasks of a common task.
  https://golang.org/x/sync/errgroup


* A universal mechanism to manage goroutine lifecycles. From **Peter Bourgon**.
  https://github.com/oklog/run


* **SizedWaitGroup** has the same role and is close to the same API as the Golang sync.WaitGroup but it adds a limit on the amount of goroutines started concurrently.
  https://github.com/remeh/sizedwaitgroup

## Rest API

TBD


## Validation

* An **idiomatic Go (golang) validation** package.
* Supports configurable and extensible validation rules (validators) using normal language constructs instead of error-prone struct tags.
  https://github.com/go-ozzo/ozzo-validation


## Common Types and Data Structures

TBD

## Profiling

* Simple **profiling** for Go.
  https://github.com/pkg/profile

## Testing

* **GoMock** is a mocking framework for the Go programming language.
  https://github.com/golang/mock


* **Testcontainers-Go** is a Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests.
  https://github.com/testcontainers/testcontainers-go


* Mocking **Context** and **Time**.
  https://github.com/benbjohnson/clock


* A toolkit with common **assertions** and mocks that play nicely with the standard library
  https://github.com/stretchr/testify


* Interface **mocking** tool for go generate.
  https://github.com/matryer/moq


* Professional lightweight **testing mini-framework** for Go.
  https://github.com/matryer/is

* **what** is a set of simple and easy logging functions suitable for tracing any kind of activity in your code. **what** can print the current function name, quickly Printf-format your data, and dump data structures. And last but not least, no **what** calls reach your production binary (unless you want it so). Debug-level logging is for developers only.
  https://github.com/appliedgocode/what

## Coding standards

TBD


## Database management

### Cassandra 

* Package **gocql** implements a fast and robust Cassandra client for the Go programming language.
  https://github.com/gocql/gocql

### ElasticSearch

* **Olivere** Go lib.
  https://github.com/olivere/elastic

## File formats handling

### XLSX 

* **Excelize** is a library written in pure Go providing a set of functions that allow you to write to and read from XLSX / XLSM / XLTM / XLTX files.
  https://github.com/qax-os/excelize 
