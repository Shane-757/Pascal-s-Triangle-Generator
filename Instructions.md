# Pascal's Triangle Generator Algorithm using Javascript

## Introduction

Pascal's Triangle is a mathematical concept named after French mathematician Blaise Pascal. It is an arithmetic triangle of numbers where each row consists of the coefficients of the binomial expansion of (a + b)^(n), where n is the row number and a, b are both 1. IF you are confused on the concept here is a more broken down version of it. https://www.mathsisfun.com/pascals-triangle.html

## Task

Generate a Pascal Triangle using purely Javascript and without any built in loop methods(forEach, filter, reduce, etc). When a user passes in a number into the parameter of the function, it should store all versions of Triangles that can be generated from 1 to userInput. The Task is completed once all test have passed
..

## Examples

```js
generateTriangle(5);
```

should return

```js
[[1], [1, 1], [1, 2, 1], [1, 3, 3, 1], [1, 4, 6, 4, 1]];
```

```js
generateTriangle(10);
```

should return

```js
[
  [1],
  [1, 1],
  [1, 2, 1],
  [1, 3, 3, 1],
  [1, 4, 6, 4, 1],
  [1, 5, 10, 10, 5, 1],
  [1, 6, 15, 20, 15, 6, 1],
  [1, 7, 21, 35, 35, 21, 7, 1],
  [1, 8, 28, 56, 70, 56, 28, 8, 1],
  [1, 9, 36, 84, 126, 126, 84, 36, 9, 1],
];
```

## Test

To run the test. Install all dependencies by using `npm install` and then run `npm run test` to run the test.
