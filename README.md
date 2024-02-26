# Clump

Clump is a project that allows users to group data efficiently.

## Installation

To use Clump, make sure you have Node.js and npm installed on your system. After that, you can install Clump by running the following command in the terminal:

``bash
npm install clump

Or, if you're using yarn, you can run:

yarn add clump

## Usage
Here is a simple usage example of Clump:

const Clump = require('clump');

const data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const chunks = Clump.chunk(data, 3);

console.log(chunks);
// Output: [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10]]

You can also perform grouping by custom size:

const Clump = require('clump');

const data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const chunks = Clump.chunk(data, 2);

console.log(chunks);
// Output: [[1, 2], [3, 4], [5, 6], [7, 8], [9, 10]]

## Contributions
If you'd like to contribute to Clump, please create a pull request and we'll be happy to receive your feedback.
