Most of this repo's code is from https://github.com/mjhea0/flaskr-tdd

# Pros and Cons of TDD

Some of the pros of Test-Driven Development are:
    - Code is written more modular as one has to write tests for each component that they plan to have in the system. Developers must think about
    the multiple interfaces/classes they create, how they will interact with other created classes and their behavours.
    - Provides a form of documentation to other developers as they can see the expected behaviour from different components. As potential inputs,
    outputs and expected behaviour of certain cases that the component will interact with are all shown within the unit tests written.

Cons of Test-Driven Development are:
    - For initial development of some application or system TDD slows development because tests must be written before actual development
    for production software can be done.
    - For larger legacy software it can be difficult to apply TDD since the components have already been implemented, and might require
    refactoring of said code and the tests that are currently written for it.