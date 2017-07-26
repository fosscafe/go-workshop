# Course Outline

GO 

Go finds application in developing network centric software, distributed computing environments and tools. Go supports automatic memory management, concurrency modelled around no-shared state and message passing. Powered by a feature rich standard library that supports I/O, text processing, cryptography, networking and many file formats and modern protocols.


LEARNING OBJECTIVE

learn Go lang programming by working through a set of modules that blend key language concepts and programming solutions to carefully crafted exercises. 

<pre>

OVERVIEW
Introduction to Go
What is Go useful for
What differentiates Go as a programming language
Architectural Overview


STRUCTURE OF A GO PROGRAM
Names
Declarations
Assignments
Type Declarations
Code Organization
Code formatting rules
gofmt
Package and Files
Scope
Block Structure

Write a Basic Program
Write a Test for the Program


PACKAGES - I
Notion of a unit of modularity
Go package
Importing paths
Package Declaration
Import Declaration
GOPATH environment variable


BASIC DATA TYPES
Notion of memory and type
Data Types and Memory
Numeric Types
Booleans
Constants
Strings


FUNCTION
Notion of a unit of work
Function declaration
Recursion
Returning multiple values
Errors


BASIC DATA TYPES - II
Notion of Memory Address
Pointers
Working with Pointers in Go


AGGREGATE DATA TYPE
Notion of contiguous memory address
Arrays
Working with Arrays


REFERENCE TYPE 
Notion of memory manipulation
Slices
Hash data structure
Map
Working with Slice and Map


FUNCTION - II
Deferred Function Calls
Function as Values
Anonymous Functions
Errors


AGGREGATE DATA TYPE - II
Notion of type that groups together multiple types
Structs
Field order
Access control for fields
Self-referential Structures
Struct literals
Struct comparison
Struct embedding
Anonymous fields


STRING FORMATTING TEMPLATES
Notion of template and action
Text Template
HTML Template


ERROR HANDLING
Notion of checks at runtime
panic
panic causes the program to crash
panic vs errors
impact of panic on deferred functions
can panic lead to memory leaks
Notion of resumption semantics
recover
recover as a mechanism for resource cleanup
when should one not recover


METHODS
Notion of function associated with a type
Declarations
Pointer Receiving
Struct embedding to compose Types
Method Values
Method Expressions
Encapsulating Methods


INTERFACES
Notion of an abstract type that defines behaviour
Interface as a contract
Interface type
Embedding an interface
Satisfying (Implementing) an interface
Assignability Rule for interface
Interface value components
Interface dynamic type
Interface dynamic value


COMMAND LINE ARGUMENTS
Notion of arguments passed externally to a program
Interface flag.Value
Parsing flags
Working with command line arguments


AGGREGATE DATA TYPE - III
Notion of serialized data for structured information
JSON format
encoding strings, numbers, booleans, arrays and objects
JSON array
JSON object
using JSON object to encode Go map and struct
Notion of 'field tags'
unifying JSON object and Go Struct using 'field tags'


FUNCTION - III
Notion of varying number of arguments
Variadic Function
ellipsis ... parameter
fmt.Printf


TESTING GO PROGRAM
Notion of White box testing
Writing Test Functions
go test
table-driven testing 
testing a command
Designing test function with dependencies
External Test package design for integration tests
Coverage Testing
Writing Benchmark tests
Profiling code


PACKAGES - II
Notion of package to modularize your own work
How to write your own package
Packages and Naming
Organizing the Code base
GOPATH variable revisited
Downloading packages
Building packages
Internal packages 
Querying packages


CONCURRENCY WITH SHARED VARIABLES
Notion of a unit of execution and shared stack
Race Condition
Mutual Exclusion


CHANNEL
Notion of synchronization by message passing
Channel
make
Multiplexing with select
Cancellation


FUNCTION - IV
Notion of a function without a stack (stackless)
embodiment of setjmp / longjmp
goroutine
writing goroutine


GROUP PROJECT
an interesting project that brings in together the conceptual learning about Go capabilities and the packages to solve the problem.

</pre>
