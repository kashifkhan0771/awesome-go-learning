# Awesome Go Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated path for learning the Go programming language, from first install to production patterns.

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)
[![Link Check](https://github.com/kashifkhan0771/awesome-go-learning/actions/workflows/link-check.yml/badge.svg)](https://github.com/kashifkhan0771/awesome-go-learning/actions/workflows/link-check.yml)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

This list is for developers who want to learn Go in a sensible order. Sections run from the basics to advanced topics, and entries inside each section run from beginner to advanced. New to Go? Follow the numbered Start Here path below. Already comfortable? Jump to any topic from the contents. Ready to work on real code? See the list of Go open source projects to contribute to under Practice & Projects.

**Legend**

- `Beginner` No prior Go knowledge needed.
- `Intermediate` Assumes you know the syntax and basic types.
- `Advanced` Internals, performance or less common libraries.
- `Free` Free to access. Some Medium posts may be behind Medium's metered paywall.
- `Paid` Requires purchase. Some have free sample chapters.

Entries with no level tag are general references useful at any stage.

## Contents

- [🧭 Start Here](#-start-here)
- [📘 Official Resources](#-official-resources)
- [🌱 Fundamentals](#-fundamentals)
- [📐 Idiomatic Go & Best Practices](#-idiomatic-go--best-practices)
- [📦 Standard Library](#-standard-library)
- [🔀 Concurrency](#-concurrency)
- [🧪 Testing](#-testing)
- [🌐 Web & APIs](#-web--apis)
- [💽 Databases](#-databases)
- [💻 CLI Tools](#-cli-tools)
- [🧰 Tooling & Code Quality](#-tooling--code-quality)
- [⚡ Performance & Memory](#-performance--memory)
- [🐳 Cloud-Native & DevOps](#-cloud-native--devops)
- [🌳 Data Structures](#-data-structures)
- [📚 Books](#-books)
- [🎥 Videos & Talks](#-videos--talks)
- [🎧 Podcasts & Newsletters](#-podcasts--newsletters)
- [🧩 Practice & Projects](#-practice--projects)
- [🔨 Build Your Own X](#-build-your-own-x)
- [💬 Community](#-community)

## 🧭 Start Here

A suggested path for complete beginners. Do these in order, then continue with the sections below.

1. [Download and Install](https://go.dev/doc/install) - `Free` Official steps for installing Go on Linux, macOS and Windows.
2. [A Tour of Go](https://go.dev/tour/welcome) - `Free` Interactive, in-browser introduction to the language, split into short exercises.
3. [Go Playground](https://go.dev/play) - `Free` Browser sandbox for running and sharing small Go programs.
4. [Go Tutorial (Golang) for Beginners](https://youtube.com/playlist?list=PL4cUxeGkcC9gC88BEo9czgyS72A3doDeM) - `Beginner` `Free` Net Ninja video playlist that walks through the language from the start.
5. [How to Write Go Code](https://go.dev/doc/code) - `Free` Official walkthrough of modules, packages and the go command for a first program.
6. [Test-Driven Development with Go](https://bitfieldconsulting.com/posts/tdd) - `Intermediate` `Free` Introduction to the TDD workflow using the testing package.
7. [Learn Go by Building a Command Line Todo App](https://www.barbarianmeetscoding.com/blog/learn-go-by-building-a-todo-cli-app) - `Intermediate` `Free` Guided project that builds a todo CLI from scratch.

## 📘 Official Resources

*Docs and tools maintained by the Go team.*

- [Documentation](https://go.dev/doc/) - `Free` Index of the official guides, tutorials and references.
- [golang/go](https://github.com/golang/go) - `Free` Source repository for the Go compiler, tools and standard library.
- [pkg.go.dev](https://pkg.go.dev/) - `Free` Search and read documentation for the standard library and public Go modules.
- [The Go Blog](https://go.dev/blog/) - `Free` Articles from the Go team on new releases, language features and best practices.
- [Effective Go](https://go.dev/doc/effective_go) - `Beginner` `Free` Official guide to writing clear, idiomatic Go.
- [Tutorial: Get Started with Go](https://go.dev/doc/tutorial/getting-started) - `Beginner` `Free` Official first tutorial: install, write Hello World and call an external package.
- [Go Modules Reference](https://go.dev/ref/mod) - `Intermediate` `Free` Detailed reference for modules, versions, the go command and proxies.
- [go.mod File Reference](https://go.dev/doc/modules/gomod-ref) - `Intermediate` `Free` Reference for every directive in a go.mod file.
- [Frequently Asked Questions](https://go.dev/doc/faq) - `Advanced` `Free` Official answers on Go's design, including how the compiler decides between stack and heap.
- [The Go Memory Model](https://go.dev/ref/mem) - `Advanced` `Free` Defines when reads in one goroutine are guaranteed to see writes from another.
- [The Go Programming Language Specification](https://go.dev/ref/spec) - `Advanced` `Free` The formal definition of the language.

## 🌱 Fundamentals

*Syntax, types and the core language.*

- [A Tour of Go: Basics](https://go.dev/tour/basics/1) - `Beginner` `Free` Packages, imports, functions, variables, basic types, constants and type conversions.
- [A Tour of Go: Flow Control](https://go.dev/tour/flowcontrol/1) - `Beginner` `Free` For loops, if and else, switch and defer.
- [A Tour of Go: More Types](https://go.dev/tour/moretypes/1) - `Beginner` `Free` Pointers, structs, arrays, slices, range, maps and function values.
- [Don't Fear the Pointer](https://bitfieldconsulting.com/posts/pointers) - `Beginner` `Free` Explains what pointers are in Go and when to use them.
- [Go by Example](https://gobyexample.com/) - `Beginner` `Free` Annotated example programs covering most of the language and common packages.
- [Go Maps: Declaring and Initializing](https://bitfieldconsulting.com/posts/map-declaring-initializing) - `Beginner` `Free` Covers the ways to declare and initialize a map.
- [Go Slices: Usage and Internals](https://go.dev/blog/slices-intro) - `Beginner` `Free` Official blog post on how slices work and how they relate to arrays.
- [Learn Golang Pointers in 179.001 Seconds](https://www.youtube.com/watch?v=v-ttLYKqaO8) - `Beginner` `Free` Three-minute video on pointer basics.
- [Practical Go Lessons](https://www.practical-go-lessons.com/) - `Beginner` `Free` Free online book that teaches Go from the basics.
- [Strings, Bytes, Runes and Characters in Go](https://go.dev/blog/strings) - `Beginner` `Free` Official blog post on how Go represents text.
- [This Is Your Last Video About Golang Structs](https://www.youtube.com/watch?v=c8H0w4yBL10) - `Beginner` `Free` Video on defining and using structs.
- [Write Packages, Not Programs](https://bitfieldconsulting.com/posts/packages) - `Beginner` `Free` Makes the case for structuring Go code as reusable packages.
- [A Tour of Go: Generics](https://go.dev/tour/generics/1) - `Intermediate` `Free` Type parameters and generic types.
- [A Tour of Go: Methods and Interfaces](https://go.dev/tour/methods/1) - `Intermediate` `Free` Methods, interfaces, type assertions, type switches, errors, readers and images.
- [Generics in Go](https://bitfieldconsulting.com/posts/generics) - `Intermediate` `Free` Shows how to move existing code to type parameters.
- [Go 101](https://go101.org/) - `Intermediate` `Free` Free online books that go deep into Go syntax, semantics and details.
- [Go Modules Explained](https://www.youtube.com/watch?v=-qh4qi4_Vpg) - `Intermediate` `Free` Video on Go modules and dependency management.
- [Go Programming: Advanced Concepts](https://www.youtube.com/playlist?list=PL7g1jYj15RUMMCMDYPyZHN3CaWbt3Rl5y) - `Intermediate` `Free` Kantan Coding video playlist on advanced Go concepts.
- [`map[string]any` in Go](https://bitfieldconsulting.com/posts/map-string-interface) - `Intermediate` `Free` When a map of empty interfaces makes sense and what it costs.
- [Master Golang with Interfaces](https://www.youtube.com/watch?v=IbXSEGB8LRs) - `Intermediate` `Free` Video on defining and using interfaces.
- [Tutorial: Getting Started with Generics](https://go.dev/doc/tutorial/generics) - `Intermediate` `Free` Official tutorial on writing generic functions with type parameters.

## 📐 Idiomatic Go & Best Practices

*Style, structure and error handling.*

- [Go Proverbs](https://go-proverbs.github.io/) - `Free` Short sayings from Rob Pike that capture the Go philosophy.
- [Standard Go Project Layout](https://github.com/golang-standards/project-layout) - `Free` Common community layout for Go repositories, not an official standard.
- [Ten Commandments of Go](https://bitfieldconsulting.com/posts/commandments) - `Free` Ten short rules for writing clear, idiomatic Go.
- [Organizing a Go Module](https://go.dev/doc/modules/layout) - `Beginner` `Free` Official guidance on laying out packages and commands in a module.
- [100 Go Mistakes](https://100go.co/) - `Intermediate` `Free` Free site summarizing common Go mistakes and how to avoid them.
- [Comparing Go Error Values](https://bitfieldconsulting.com/posts/comparing-errors) - `Intermediate` `Free` How to compare and check error values.
- [Go Code Review Comments](https://go.dev/wiki/CodeReviewComments) - `Intermediate` `Free` Common review feedback from the Go team, a checklist for idiomatic code.
- [Google Go Style Guide](https://google.github.io/styleguide/go/) - `Intermediate` `Free` Google's style guide, decisions and best practices for Go.
- [Handling Errors Like a 10x Engineer in Golang](https://www.youtube.com/watch?v=CxcxRgwWtAk) - `Intermediate` `Free` Video on an error-handling pattern for Go services.
- [Practical Go](https://dave.cheney.net/practical-go/presentations/qcon-china.html) - `Intermediate` `Free` Dave Cheney's advice on writing maintainable Go programs.
- [Uber Go Style Guide](https://github.com/uber-go/guide) - `Intermediate` `Free` Uber's conventions for writing Go in a large codebase.
- [Working with Errors in Go 1.13](https://go.dev/blog/go1.13-errors) - `Intermediate` `Free` Official post on wrapping errors and using errors.Is and errors.As.
- [Standard Package Layout](https://www.gobeyond.dev/standard-package-layout/) - `Advanced` `Free` Ben Johnson's approach to organizing packages in an application.

## 📦 Standard Library

*Packages that ship with Go.*

- [Container List Package](https://www.youtube.com/watch?v=O75tp0medyo) - `Beginner` `Free` Video walkthrough of container/list.
- [container/list](https://pkg.go.dev/container/list) - `Beginner` `Free` Official docs for the doubly linked list package.
- [Demystifying Golang Strings](https://medium.com/@andreiboar/demystifying-golang-strings-05981b84f1a7) - `Beginner` `Free` Explains how strings work in Go.
- [Go by Example: Regular Expressions](https://gobyexample.com/regular-expressions) - `Beginner` `Free` Annotated example of the common regexp functions.
- [How to Use and Implement the strconv Package](https://www.educative.io/answers/how-to-use-and-implement-strconv-package-in-golang) - `Beginner` `Free` Short guide to converting between strings and numbers.
- [Math Package](https://www.youtube.com/watch?v=lI-ja3d3aqM) - `Beginner` `Free` Video walkthrough of the math package.
- [math Package in Golang](https://www.geeksforgeeks.org/go-language/math-package-in-golang/) - `Beginner` `Free` Overview of the math package.
- [os](https://pkg.go.dev/os) - `Beginner` `Free` Official docs for files, processes and environment access.
- [OS Package](https://www.youtube.com/watch?v=ymMBsfCZI3s) - `Beginner` `Free` Video walkthrough of the os package.
- [Regex Package](https://www.youtube.com/watch?v=ZmguDIDeolk) - `Beginner` `Free` Video walkthrough of the regexp package.
- [Strconv Package](https://www.youtube.com/watch?v=sRJMtZn1Yl0) - `Beginner` `Free` Video walkthrough of the strconv package.
- [String Package](https://www.youtube.com/watch?v=WaoT7EtdY_g) - `Beginner` `Free` Video walkthrough of the strings package.
- [Everything About Basic File Handling in Golang](https://www.youtube.com/watch?v=dqvvN0WXU_M) - `Intermediate` `Free` Video on creating, reading, writing and deleting files.
- [File I/O in Go](https://dev.to/romulogatto/file-io-in-go-488d) - `Intermediate` `Free` Article on reading and writing files.
- [How to Send and Parse JSON Data in Golang](https://www.freecodecamp.org/news/encoding-and-decoding-data-in-golang/) - `Intermediate` `Free` Encoding and decoding JSON with encoding/json, with examples.
- [JSON Encoding and Decoding in Golang](https://www.youtube.com/watch?v=Vr63uGL7NrU) - `Intermediate` `Free` BugBytes video on encoding and decoding JSON.
- [Mastering Regular Expressions in Go](https://www.honeybadger.io/blog/a-definitive-guide-to-regular-expressions-in-go/) - `Intermediate` `Free` Guide to regular expression syntax and the regexp package.
- [Regular Expression Basics for Go Programmers](https://www.youtube.com/watch?v=nDiFzmGFjS8) - `Intermediate` `Free` AppliedGo video on regex syntax as used in Go.
- [Time Package](https://www.youtube.com/watch?v=PH1be4qdgWM) - `Intermediate` `Free` Video walkthrough of the time package.
- [Working with Time Data in Go](https://dev.to/jpoly1219/time-in-go-jlc) - `Intermediate` `Free` Article on working with time values in Go.
- [Deep Dive Into Go's reflect Package](https://dev.to/doziestar/deep-dive-into-go-reflect-package-baa) - `Advanced` `Free` Article on inspecting types and values at runtime.
- [How to Stream Large Files Over TCP in Golang](https://www.youtube.com/watch?v=82oFmY-Qeok) - `Advanced` `Free` Anthony GG video on sending large files without loading them into memory.
- [Reflect Package](https://www.youtube.com/watch?v=ZGZU37A2p2E) - `Advanced` `Free` Video walkthrough of the reflect package.
- [The Laws of Reflection](https://go.dev/blog/laws-of-reflection) - `Advanced` `Free` Official post explaining how reflection works in Go.

## 🔀 Concurrency

*Goroutines, channels, synchronization and context.*

- [A Tour of Go: Concurrency](https://go.dev/tour/concurrency/1) - `Intermediate` `Free` Goroutines, channels, buffered channels, select and sync.Mutex.
- [Concurrency Is Not Parallelism](https://go.dev/blog/waza-talk) - `Intermediate` `Free` Rob Pike's talk on the difference between the two ideas.
- [Go Concurrency Patterns](https://www.youtube.com/watch?v=f6kdp27TYZs) - `Intermediate` `Free` Google I/O 2012 talk on composing goroutines and channels.
- [Go Concurrency Patterns: Context](https://go.dev/blog/context) - `Intermediate` `Free` Official post introducing the context package.
- [Go Go Goroutines](https://bitfieldconsulting.com/posts/goroutines) - `Intermediate` `Free` Explains Go's concurrency model and how goroutines run.
- [golang context package explained](https://www.youtube.com/watch?v=8omcakb31xQ) - `Intermediate` `Free` Video on cancellation, deadlines and values with context.
- [Racing with Disaster: Data Races in Go](https://bitfieldconsulting.com/posts/racing-with-disaster) - `Intermediate` `Free` What data races are and how to find them with the race detector.
- [Share Memory By Communicating](https://go.dev/blog/codelab-share) - `Intermediate` `Free` Official post on using channels instead of shared memory and locks.
- [Starving, Sleeping, and Yielding](https://bitfieldconsulting.com/posts/starving) - `Intermediate` `Free` Explains how the Go scheduler shares CPU time between goroutines.
- [The Complete Guide to Context in Golang](https://medium.com/@jamal.kaksouri/the-complete-guide-to-context-in-golang-efficient-concurrency-management-43d722f6eaea) - `Intermediate` `Free` Long-form article on using the context package to manage concurrent work.
- [This Is Why Go Channels Are Awesome](https://www.youtube.com/watch?v=nNXhePi3xwE) - `Intermediate` `Free` Video introduction to channels.
- [Using WaitGroups and Goroutines](https://www.youtube.com/watch?v=PCoTAkTNrU4) - `Intermediate` `Free` Video on waiting for a group of goroutines with sync.WaitGroup.
- [Go Concurrency Patterns: Pipelines and Cancellation](https://go.dev/blog/pipelines) - `Advanced` `Free` Official post on building pipelines with channels and stopping them cleanly.
- [Go Singleflight Melts in Your Code, Not in Your DB](https://victoriametrics.com/blog/go-singleflight/) - `Advanced` `Free` VictoriaMetrics post on deduplicating concurrent calls with singleflight.
- [Optimizing Concurrency in Go with Single Flight](https://www.youtube.com/watch?v=Gpnm6SFNx_w) - `Advanced` `Free` Video on preventing duplicate work with singleflight.

## 🧪 Testing

*Unit tests and test-driven development.*

- [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests) - `Beginner` `Free` Free book that teaches Go and TDD together, one test at a time.
- [Programming with Confidence: TDD in Go](https://bitfieldconsulting.com/posts/tdd-programming-confidence) - `Intermediate` `Free` Why writing tests first leads to better Go code.
- [Shameless Green: Pragmatic TDD in Go](https://bitfieldconsulting.com/posts/tdd-shameless-green) - `Intermediate` `Free` Getting a test to pass with the simplest code, then refactoring.
- [testify](https://github.com/stretchr/testify) - `Intermediate` `Free` Popular assertion and mocking toolkit for Go tests.
- [Tutorial: Getting Started with Fuzzing](https://go.dev/doc/tutorial/fuzz) - `Intermediate` `Free` Official tutorial on writing and running fuzz tests.

## 🌐 Web & APIs

*HTTP servers, clients and REST APIs.*

- [Alex Edwards' Blog](https://www.alexedwards.net/blog) - `Free` Practical articles on Go web development.
- [Let's Go](https://lets-go.alexedwards.net/) - `Beginner` `Paid` Alex Edwards' book on building a full web application with Go.
- [Tutorial: Developing a RESTful API with Go and Gin](https://go.dev/doc/tutorial/web-service-gin) - `Beginner` `Free` Official tutorial that builds a small REST API with Gin.
- [An API Client in Go](https://bitfieldconsulting.com/posts/api-client) - `Intermediate` `Free` Step-by-step build of a client package for a REST API.
- [Building a Basic API in Go](https://medium.com/@jealousgx/building-a-basic-api-in-go-a-beginners-guide-82fc1c6a0d57) - `Intermediate` `Free` Beginner's guide to building a simple REST API.
- [Chi](https://github.com/go-chi/chi) - `Intermediate` `Free` Lightweight router built on net/http.
- [DIY Golang Web Server](https://www.youtube.com/watch?v=eqvDSkuBihs) - `Intermediate` `Free` Video on building a web server with only the standard library.
- [Echo](https://echo.labstack.com/) - `Intermediate` `Free` Documentation for the Echo web framework.
- [Gin](https://gin-gonic.com/) - `Intermediate` `Free` Documentation for the Gin web framework.
- [How I Write an API Client in Golang](https://www.youtube.com/watch?v=DawS6OHPFc0) - `Intermediate` `Free` Video on structuring and testing an HTTP API client.
- [Mastering Go Web Servers](https://dev.to/leapcell/mastering-go-web-servers-from-zero-to-hero-58i3) - `Intermediate` `Free` Article on building web servers in Go.
- [The Standard Library Now Has All You Need for Advanced Routing](https://www.youtube.com/watch?v=H7tbjKFSg58) - `Intermediate` `Free` Dreams of Code video on routing with net/http's ServeMux.
- [Fiber](https://docs.gofiber.io/) - `Advanced` `Free` Official documentation for the Fiber web framework.
- [Let's Go Further](https://lets-go-further.alexedwards.net/) - `Advanced` `Paid` Alex Edwards' follow-up book on building JSON APIs and advanced web patterns.

## 💽 Databases

*Working with data stores.*

- [Tutorial: Accessing a Relational Database](https://go.dev/doc/tutorial/database-access) - `Beginner` `Free` Official tutorial on querying a database with database/sql.
- [GORM](https://gorm.io/) - `Intermediate` `Free` Documentation for GORM, a widely used ORM for Go.
- [pgx](https://github.com/jackc/pgx) - `Intermediate` `Free` PostgreSQL driver and toolkit for Go.
- [sqlc](https://sqlc.dev/) - `Intermediate` `Free` Generates type-safe Go code from SQL queries.
- [How to Use the Official MongoDB Go Driver](https://medium.com/@wembleyleach/how-to-use-the-official-mongodb-go-driver-9f8aff716fdb) - `Advanced` `Free` Article on connecting to MongoDB with the official Go driver.
- [Quick Start: Connect to Your MongoDB Cluster with Go](https://www.youtube.com/watch?v=JNr5noDp6EM) - `Advanced` `Free` MongoDB's own video on connecting from a Go program.

## 💻 CLI Tools

*Command-line apps, flags and configuration.*

- [A Guide to Configuration Management in Go with Viper](https://dev.to/kittipat1413/a-guide-to-configuration-management-in-go-with-viper-5271) - `Intermediate` `Free` Article on managing application configuration with Viper.
- [Amazing Golang Configuration with Viper](https://www.youtube.com/watch?v=IP1VXYpO4B8) - `Intermediate` `Free` Video on setting up Viper for app configuration.
- [Building Helpful CLI Tools with Go and Kingpin](https://www.atlassian.com/blog/developer/building-helpful-golang-cli-tools) - `Intermediate` `Free` Atlassian post on building CLIs with the Kingpin parser.
- [Cobra CLI Explained](https://www.youtube.com/watch?v=WlStlWsEl70) - `Intermediate` `Free` Video on building CLI apps with Cobra.
- [Cobra Tutorials](https://cobra.dev/docs/tutorials/) - `Intermediate` `Free` Official tutorials for the Cobra CLI framework.
- [Create a CLI with Go and Cobra](https://www.youtube.com/watch?v=_zpjJ8_TM3I) - `Intermediate` `Free` Video building a CLI app with Cobra from scratch.
- [flag](https://pkg.go.dev/flag) - `Intermediate` `Free` Official docs for the standard library flag parser.
- [Flag Package](https://www.youtube.com/watch?v=ChV8Gc1G2Vc) - `Intermediate` `Free` Video walkthrough of the flag package.
- [Go Development Command Line Program Guide](https://www.sobyte.net/post/2023-03/go-command-line/) - `Intermediate` `Free` Guide to writing command-line programs in Go.
- [Developing a Terminal App in Go with Bubble Tea](https://www.youtube.com/watch?v=_gzypL-Qv-g) - `Advanced` `Free` Video building a terminal UI with Bubble Tea.
- [Intro to Bubble Tea in Go](https://dev.to/andyhaskell/intro-to-bubble-tea-in-go-21lg) - `Advanced` `Free` Introductory article on building terminal UIs with Bubble Tea.

## 🧰 Tooling & Code Quality

*Linters, static analysis and security checks.*

- [golangci-lint](https://golangci-lint.run/) - `Intermediate` `Free` Runs many Go linters in one fast tool.
- [Staticcheck](https://staticcheck.dev/) - `Intermediate` `Free` Static analysis tool that finds bugs and simplifications.
- [Tutorial: Find and Fix Vulnerable Dependencies with govulncheck](https://go.dev/doc/tutorial/govulncheck) - `Intermediate` `Free` Official tutorial on scanning a module for known vulnerabilities.

## ⚡ Performance & Memory

*Garbage collection, allocation and caching.*

- [A Guide to the Go Garbage Collector](https://go.dev/doc/gc-guide) - `Advanced` `Free` Official explanation of how the GC works and how to tune GOGC and the memory limit.
- [Diagnostics](https://go.dev/doc/diagnostics) - `Advanced` `Free` Official overview of profiling, tracing and debugging tools for Go.
- [golang-lru](https://github.com/hashicorp/golang-lru) - `Advanced` `Free` HashiCorp's LRU cache library, including an expirable variant.
- [High Performance Go Workshop](https://dave.cheney.net/high-performance-go-workshop/dotgo-paris.html) - `Advanced` `Free` Dave Cheney's workshop on benchmarking, profiling and reducing allocations.
- [Implementing Caching with Sync Map in Golang](https://www.youtube.com/watch?v=mhDRQqsBX6U) - `Advanced` `Free` Video on building an in-memory cache with sync.Map.
- [Let's Make a Cache in Go](https://uncomputation.medium.com/lets-make-a-cache-in-go-ea49fc9ebe93) - `Advanced` `Free` Builds an in-memory cache step by step, with tests.
- [Profile-Guided Optimization](https://go.dev/doc/pgo) - `Advanced` `Free` Official guide to using CPU profiles to let the compiler optimize builds.
- [Profiling Go Programs](https://go.dev/blog/pprof) - `Advanced` `Free` Official post on finding hot spots with pprof.
- [Stack vs Heap Memory](https://www.youtube.com/watch?v=5OJRqkYbK-4) - `Advanced` `Free` Video explaining the difference between stack and heap memory.
- [Why Go's Garbage Collection Is a Game Changer](https://www.youtube.com/watch?v=_ThztMZoZeo) - `Advanced` `Free` Video on how Go's garbage collector works.
- [Zero Allocation in Go](https://medium.com/@ksandeeptech07/zero-allocation-in-go-ce29e6a9ffdc) - `Advanced` `Free` Techniques for writing Go code that avoids heap allocations.

## 🐳 Cloud-Native & DevOps

*Containers and cloud services.*

- [Go Language-Specific Guide](https://docs.docker.com/guides/golang/) - `Intermediate` `Free` Docker's guide to containerizing, testing and deploying a Go app.
- [Go Cloud Development Kit](https://gocloud.dev/) - `Advanced` `Free` Portable APIs for common cloud services across providers.

## 🌳 Data Structures

*Classic data structures implemented in Go.*

- [TheAlgorithms/Go](https://github.com/TheAlgorithms/Go) - `Beginner` `Free` Collection of algorithms and data structures implemented in Go.
- [Binary Search Tree](https://www.youtube.com/watch?v=Id099WXOKNM) - `Intermediate` `Free` JamieGo video implementing a binary search tree.
- [Hash Tables](https://www.youtube.com/watch?v=JCXLwfKMWOU) - `Intermediate` `Free` JamieGo video implementing a hash table.
- [Linked List](https://www.youtube.com/watch?v=zgAwMts9bRg) - `Intermediate` `Free` JamieGo video implementing a linked list, part 1 of 2.
- [Stacks and Queues](https://www.youtube.com/watch?v=Ozkr6fckWrE) - `Intermediate` `Free` JamieGo video implementing stacks and queues.
- [The Trie Data Structure](https://www.youtube.com/watch?v=H-6-8_p88r0) - `Intermediate` `Free` JamieGo video implementing a trie.

## 📚 Books

*Books worth paying for.*

- [Learning Go, 2nd Edition](https://www.oreilly.com/library/view/learning-go-2nd/9781098139285/) - `Beginner` `Paid` Jon Bodner's introduction to idiomatic Go for developers new to the language.
- [100 Go Mistakes and How to Avoid Them](https://www.manning.com/books/100-go-mistakes-and-how-to-avoid-them) - `Intermediate` `Paid` Teiva Harsanyi's book on common mistakes, with explanations and fixes.
- [Concurrency in Go](https://www.oreilly.com/library/view/concurrency-in-go/9781491941294/) - `Intermediate` `Paid` Katherine Cox-Buday's book on Go's concurrency primitives and patterns.
- [The Go Programming Language](https://www.gopl.io/) - `Intermediate` `Paid` Donovan and Kernighan's classic book covering the whole language.
- [Writing An Interpreter In Go](https://interpreterbook.com/) - `Intermediate` `Paid` Thorsten Ball's book that builds an interpreter from scratch.
- [Writing A Compiler In Go](https://compilerbook.com/) - `Advanced` `Paid` Thorsten Ball's follow-up that builds a compiler and virtual machine.

## 🎥 Videos & Talks

*Background on why Go exists.*

- [Gopher Academy](https://www.youtube.com/@GopherAcademy) - `Free` YouTube channel with recorded GopherCon talks.
- [Ken Thompson: Why Did We Create Golang?](https://www.youtube.com/watch?v=c-P5R0aMylM) - `Free` Short clip of Ken Thompson on the motivation behind Go.
- [The Why of Go](https://www.youtube.com/watch?v=bmZNaUcwBt4) - `Free` InfoQ talk on the problems Go was designed to solve.
- [Thompson Tells How He Developed the Go Language at Google](https://www.youtube.com/watch?v=NTrAISNdf70) - `Free` Ken Thompson on how Go was started at Google.

## 🎧 Podcasts & Newsletters

*Stay current.*

- [Cup o' Go](https://cupogo.dev/) - `Free` Weekly podcast with Go news.
- [Go Time](https://changelog.com/gotime) - `Free` Changelog podcast about Go, ended in December 2024 with its archive still available.
- [Golang Weekly](https://golangweekly.com/) - `Free` Weekly newsletter with Go articles, news and releases.

## 🧩 Practice & Projects

*Build something.*

- [Go Open Source Projects to Contribute To](https://github.com/kashifkhan0771/awesome-go-learning/blob/main/OPEN_SOURCE_PROJECTS.md) - `Free` Companion list of 51 well-known Go projects that welcome contributors, with links to their beginner issues.
- [kashifkhan0771/golang](https://github.com/kashifkhan0771/golang) - `Free` Collection of example Go programs.
- [Exercism Go Track](https://exercism.org/tracks/go) - `Beginner` `Free` Coding exercises with optional mentor feedback.
- [Gophercises](https://gophercises.com/) - `Beginner` `Free` Free video exercises that each build a small Go program.

## 🔨 Build Your Own X

*Rebuild a familiar tool from scratch to learn how it works. Go entries collected from [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x).*

- [Build a Command Line App with Go: lolcat](https://flaviocopes.com/go-tutorial-lolcat/) - `Free` Tutorial that builds a clone of the lolcat command.
- [Build a Multilayer Perceptron with Golang](https://made2591.github.io/posts/neuralnetwork) - `Free` Implements a multilayer perceptron neural network in Go.
- [Build a Simple Terminal Emulator in 100 Lines of Golang](https://ishuah.com/2021/03/10/build-a-terminal-emulator-in-100-lines-of-go/) - `Free` Builds a minimal terminal emulator in about 100 lines.
- [Build Your Own Container Using Less than 100 Lines of Go](https://www.infoq.com/articles/build-a-container-golang) - `Free` InfoQ article that builds a basic Linux container in Go.
- [Build Your Own Database from Scratch](https://build-your-own.org/database/) - `Paid` Book that goes from a B+tree to a small SQL database in Go. Part I is free to read online.
- [Build Your Own Redis from Scratch](https://www.build-redis-from-scratch.dev/) - `Free` Step-by-step guide to building your own Redis in Go.
- [Building a BitTorrent Client from the Ground Up in Go](https://blog.jse.li/posts/torrent/) - `Free` Walks through writing a client that downloads files over BitTorrent.
- [Building a CLI Command with Go: cowsay](https://flaviocopes.com/go-tutorial-cowsay/) - `Free` Tutorial that builds a clone of the cowsay command.
- [Building a Neural Net from Scratch in Go](https://datadan.io/blog/neural-net-with-go) - `Free` Implements a simple neural network without external libraries.
- [Building Blockchain in Go](https://jeiwan.net/posts/building-blockchain-in-go-part-1/) - `Free` Multi-part series that builds a simplified blockchain.
- [Code a Database in 45 Steps](https://trialofcode.org/database/) - `Free` Series of small test-driven coding puzzles that add up to a database.
- [Code Your Own Blockchain in Less than 200 Lines of Go](https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc) - `Free` Short tutorial that builds a minimal blockchain.
- [Containers From Scratch](https://www.youtube.com/watch?v=8fi7uSYlOdc) - `Free` Liz Rice's GOTO 2018 talk on building a container from scratch in Go.
- [Games With Go](https://www.youtube.com/playlist?list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - `Free` Jack Mott's video series on programming games in Go.
- [Go CLI Tutorial: fortune clone](https://flaviocopes.com/go-tutorial-fortune/) - `Free` Tutorial that builds a clone of the fortune command.
- [How to Build a Regex Engine from Scratch](https://rhaeguard.github.io/posts/regex) - `Free` Writes a regular expression engine in Go.
- [How to Build a Simple Artificial Neural Network with Go](https://sausheong.github.io/posts/how-to-build-a-simple-artificial-neural-network-with-go/) - `Free` Builds a basic artificial neural network in Go.
- [Let's Create a Simple Load Balancer](https://kasvith.me/posts/lets-create-a-simple-lb-go/) - `Free` Builds a simple load balancer in Go.
- [Lexical Scanning in Go](https://www.youtube.com/watch?v=HxaD_trXwRE) - `Free` Rob Pike's talk on how to design and write a lexer in Go.
- [The Super Tiny Compiler](https://github.com/hazbo/the-super-tiny-compiler) - `Free` Minimal compiler written in Go.
- [Video Encoding from Scratch](https://github.com/kevmo314/codec-from-scratch) - `Free` Builds a simple video codec from scratch.
- [Visualize Your Local Git Contributions with Go](https://flaviocopes.com/go-git-contributions/) - `Free` Tutorial that builds a CLI to visualize your local Git contributions.

## 💬 Community

*Ask questions and meet other Gophers.*

- [awesome-go](https://github.com/avelino/awesome-go) - `Free` Curated list of Go frameworks, libraries and software.
- [Go Forum](https://forum.golangbridge.org/) - `Free` Discussion forum for questions about Go.
- [Gophers Slack](https://invite.slack.golangbridge.org/) - `Free` Large Slack workspace for Go developers.
- [r/golang](https://www.reddit.com/r/golang/) - `Free` Reddit community for Go news and discussion.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first, and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

This list is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
