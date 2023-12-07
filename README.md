![image](https://github.com/bifrostsimple/calculator/assets/142265814/987c6f10-0c92-4b01-904b-2de7ee523245)Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/Trackly/Calculator/_apis/build/status%2Fbifrostsimple.calculator?branchName=master)](https://dev.azure.com/Trackly/Calculator/_build/latest?definitionId=6&branchName=master)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

