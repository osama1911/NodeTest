>
> # Testing APIs
>
> ## Sketch
>
> The example code will use koa/express. It does not make a big difference.
> If we will have the time we can do it for both.
>
> 1. Unit tests in general
> 2. Integration tests in general
> 3. How to structure your code, so it can be easily tested
> 4. Using a test runner (mocha)
> 5. Writing unit tests
>   - how to mock databases (using sinon)
> 6. Writing integration tests with hippie
>   - when writing integration tests, we do not mock out the database
> 7. Mocking out APIs using nock (example: integration testing microservices)

# Writing testable REST APIs

I remember writing my first test-cases - it was everything but nice and clean. Testing done right is not easy.
It is not just about how you write your tests, but also how you structure your entire codebase.
This post intends to clear that up in the context of REST APIs.

## Unit tests

Unit tests are the basic building block of tests, where each test case is independent from
others. The goal of unit tests to individually test if parts of the application are correct.

Also, unit tests provide a living documentation of the system. Your fellow developer can look
at your tests, and get a basic understanding of what is going on in your modules.

## Integration tests

## Setting up your test runner

## Making your codebase modular - time for unit tests

## Putting the pieces together - writing integration tests

## Mock out third-party APIs
