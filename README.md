# JavaScript: Raindrops

Write a program that converts a number to a string, the contents of which depend on the number's factors.

- If the number has 3 as a factor, output 'Pling'.
- If the number has 5 as a factor, output 'Plang'.
- If the number has 7 as a factor, output 'Plong'.
- If the number does not have 3, 5, or 7 as a factor,
  just pass the number's digits straight through.

## Examples

- 28's factors are 1, 2, 4, **7**, 14, 28.
  - In raindrop-speak, this would be a simple "Plong".
- 30's factors are 1, 2, **3**, **5**, 6, 10, 15, 30.
  - In raindrop-speak, this would be a "PlingPlang".
- 34 has four factors: 1, 2, 17, and 34.
  - In raindrop-speak, this would be "34".

These tests use jasmine-node, which is a testing framework written for Node.js.

You will need:

* Node.js
* The Node Package Manager (NPM)
* jasmine-node

You can install both Node.js and NPM with a download from nodejs.org: https://nodejs.org/en/download

Use NPM to install jasmine-node:

    npm install jasmine-node -g

To work on an exercise, change to the directory of the exercise:

    cd hello-world

This contains the files for the exercise.

    .
    ├── README.md
    └── hello-world.spec.js

To run a test file, pass it as an argument to the `jasmine-node` command:

    jasmine-node hello-world.spec.js

## Source

A variation on a famous interview question intended to weed out potential candidates. [http://jumpstartlab.com](http://jumpstartlab.com)

This exercise is from the [JavaScript][javascript] track on [Exercism][exercism]

[exercism]: http://exercism.io
[javascript]: http://exercism.io/languages/javascript



