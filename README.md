# DataStructures-Algorithms-JavaScript
JavaScript Algorithm Implementations: Explore my practical JavaScript solutions showcasing the synergy between algorithms and data structures for effective problem-solving.
// Recursive function to calculate factorial
function factorial(n) {
  if (n === 0 || n === 1) {
    return 1;
  } else {
    return n * factorial(n - 1);
  }
}

// Calculate factorial of a number
const num = 5;
const result = factorial(num);

console.log(`Factorial of ${num} is ${result}`);
