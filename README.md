# Reactor training

Spring [Reactor](https://projectreactor.io) hands-on training (3 days)


## Day 1: Introduction

- What is reactive programming
- Crash course to `CompletableFuture` and thread pools
- Introducing Reactor
- How to create a stream?
- Laziness
- Basic operators
  - `map()`, `filter()`, `flatMap()`, `handle()`, `take()`, `skip()`
  - `using()`, `do*()`
  - `window()`, `buffer()`
- Error handling
  - `onError*()`, `retry*()`
- Blocking and reactive, back and forth
- Concurrency with blocking code and thread pools
- Unit testing

## Day 2: Reactor advanced
- Concurrency with non-blocking code
- Advanced error handling and retries
- `transform()` vs. `compose()`
- Backpressure
- `Processor` API
  - `Unicast`, `Emitter`, `Replay`
- Advanced testing with virtual time
- `Context`
- [RxJava](https://github.com/ReactiveX/RxJava) interoperability

## Day 3: Practical
- Refactoring existing application to Reactor
- [Spring Boot](https://spring.io/projects/spring-boot)
  - Reactive database access
  - Reactive controllers
- Streaming data in and out
- Troubleshooting and debugging
  - `checkpoint()`, `onOperatorDebug()`, `doOn*()`
