# Incorrect Null Handling in JavaScript Function

This repository demonstrates a common error in JavaScript: incorrect handling of null values. The `foo` function in `bug.js` attempts to add two numbers but returns `null` if either input is `null`. This behavior is often incorrect and can lead to unexpected results.

The correct approach is to handle `null` values appropriately, for instance, by returning 0 or throwing an error. The corrected version is provided in `bugSolution.js`.

## How to run

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred code editor.
3. Run the code using a JavaScript runtime (e.g., Node.js).

## License

This project is licensed under the MIT License - see the LICENSE file for details.