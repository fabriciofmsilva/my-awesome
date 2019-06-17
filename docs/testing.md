# Testing

## Table of Contents

* [Unit](#unit)
* [Integration](#integration)
* [Component](#component)
* [Contract](#contract)
* [End-to-End](#end-to-end)
* Exploratory
* [Miscellneous](#miscellaneous)
* Functional
* Mocks
* Stubs

* Unit Tests: Testing of individual functions or classes by giving them an input and testing the output.
* Integration Tests: Testing processes or components to behave as expected (including side effects).
* End to End (UI) Tests- testing actual behaviour of your user and going beyond just a simple function. Testing human actions and behaviours.

## Unit

Exercise the smallest pieces of testable software in the application to determine whether they behave as expected.

* [Jest](https://jestjs.io/)
* [Mocha](https://mochajs.org/) + [Chai](https://www.chaijs.com/) + [Sinon](https://sinonjs.org/) + [Istanbul](https://istanbul.js.org/)

Sociable unit testing (black box tested), Solitary unit testing (test doubles)

## Integration

Verify the communication paths and interactions between components to detect interface defects.

Gateway integration tests, Persistence integration tests

## Component

Limit the scope of the exercised software to a portion of the system under test, manipulating the system through nternal code interfaces and using test doubles to isolate the code under test from other components.

* [Inproctester](https://github.com/aharin/inproctester)
* [Plasma](https://github.com/plasma-dot-net/plasma)
* [Moco](https://github.com/dreamhead/moco)
* [stubby4j](https://github.com/azagniotov/stubby4j)
* [Mountebank](https://github.com/bbyars/mountebank)
* [vcr](https://github.com/vcr/vcr)

## Contract

Verify interactions at the boundary of an external service asserting that it meets the contract expected by a consuming service.

* [Pact](https://github.com/realestate-com-au/pact)
* [Pacto](https://github.com/thoughtworks/pacto)
* [Janus](https://github.com/gga/janus)

## End-to-End

Verify that a system meets external requirements and achieves its goals, testing the entire system, from end to end.

Write as few end-to-end tests as possible

time budget -> in minutes, not hours.

Another names -> BroadStackTest; full-stack test

* [Selenium](https://www.seleniumhq.org/)
* [Cypress](https://www.cypress.io/)
* [Nightwatch](http://nightwatchjs.org/)
* [Protractor](https://www.protractortest.org/) (for Angular lovers)
* [Gauge](https://gauge.org/index.html)
* [Concordion](https://concordion.org/)

## Miscellaneous

Mocks, Spies, Stubs, and Snapshot Testing

Shim

Test Pyramid, UI tests, customer facing tests

* [Jasmine](https://jasmine.github.io/)

## Articles

* [TestPyramid](https://martinfowler.com/bliki/TestPyramid.html)
* [Testing Strategies in a Microservice Architecture](https://martinfowler.com/articles/microservice-testing/)
