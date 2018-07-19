## FizzBuzz
FizzBuzz is a very popular programming exercise.

### Getting Started
In order to beef up our skills with [Git](https://git-scm.com/), it is highly recommended that you fork this repository to your profile and clone your fork to your local machine:
- [Fork](https://help.github.com/articles/fork-a-repo/) this repository.
- Clone your fork to your local machine: `$ git clone https://github.com/<YOUR_GITHUB_USERNAME>/fizzbuzz.git`
  - The `$` is a common way to indicate that this command should be run in your terminal. Do not include it when typing the command.
- Change Directory into the newly cloned fizzbuzz project: `$ cd fizzbuzz`
- Open in the project in your favorite text editor, and edit the `app.js` file!
- You must open your `index.html` file in Chrome, and use the [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/) to see your code running in the Console tab.
  - Remember to refresh the browser whenever you make a change to your codebase.

### Description
- Write a program that console.logs the numbers 1 through 100.
- For multiples of 3, console.log('Fizz') instead of the number.
- For multiples of 5, console.log('Buzz') instead of the number.
- For numbers which are multiples of both 3 and 5, console.log('FizzBuzz') instead of the number.

### Objective
- To reinforce your understanding of flow control and comparison operators.

### Notes
- If you do not yet feel comfortable with `git`, go ahead and create your own project on your local machine and attempt to solve the problem there.
- (Hint) The solution will most likely require the use of the [Remainder operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Remainder_()): `%`

Example usage of `%`:
```javascript
12 % 5 === 2
15 % 5 === 0
6 % 3 === 0

if (6 % 3 === 0) {
  console.log('The remainder of 6 / 3 is 0')
}
```

