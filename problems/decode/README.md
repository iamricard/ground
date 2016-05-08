Decode
======

Assumptions
-----------
Basic knowledge of the following is expected:

* Array (how to define one, how to access its values)

If you do not think you know that, please make sure to click on the
superscript links you will find throughout the README and familiarize
yourself with the documentation they link to before continuing.

Exercise
--------

In this exercise you are expected to `export` a `Function`[¹], the
boilerplate is created for you in `main.js`, which should take
one argument of type `Array`[²], and return a `string`[³].

The array will contain more `array`s. The inner `array`s will contain
`string`s. Taking the first letter of every word in those arrays you
you will be able to get words to form the actual message. Each final
word is contained inside an `array`. An example is as follows:

```js
[
  ['hike', 'enterprise', 'lake', 'long', 'offer'],
  ['what', 'official', 'renegade', 'last', 'dragon']
]

// The result should be:

'hello world'
```

Please make sure you read through **every step**.

If at any point you want to try your solution, run:

```sh
$ TEST=decode npm test
```

Step one
--------
In JavaScript, as in most other programming languages, you are
provided with a very powerful construct to go through a `collection`
of information referred to as `loop`.

> When using JavaScript, typically a collection will be an `Array`,
That will not always be the case in every programming language.
Even in JavaScript we have `Object`[⁴]s, which are a different type
of collection. For now though, we will assume that every collection
is an `Array`.

### For loop

There are basic ways to loop through collection in JavaScript and in
most other languages. We will ignore `while`[⁵], and focus on the
`for`[⁶] construct. Here's an example on how to use a `for` loop:

```js
for (let i = 0; i < 5; i++) {
  console.log(i)
}

/*
 * Will output:
 * 1
 * 2
 * 3
 * 4
 * 5
 */
```

For the first step you are only allowed to use this construct to
solve the problem.

[¹]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function
[²]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
[³]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String
[⁴]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
[⁵]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while
[⁶]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for
