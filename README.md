# Triangle Test Case Exercise

This project is an interactive web-based exercise designed to help users practice creating test cases for a simple triangle classification program. It's an excellent tool for learning about software testing principles and the challenges of comprehensive test case design.

## Purpose

The main goals of this exercise are to:

1. Demonstrate the complexity of testing even simple programs
2. Encourage critical thinking about edge cases and various scenarios
3. Provide immediate feedback on the completeness of test cases
4. Introduce concepts of black-box testing and boundary value analysis

## How It Works

The exercise presents users with a description of a hypothetical program that classifies triangles based on their side lengths. Users are then asked to input test cases that would thoroughly test this program.

The system evaluates the provided test cases based on various criteria, including:

- Valid triangles (scalene, isosceles, equilateral)
- Invalid triangles (zero or negative side lengths, sum of two sides not greater than the third)
- Edge cases (all sides zero, non-integer values, incorrect number of values)

After evaluation, users receive a score and detailed feedback on their test case coverage.

## How to Use

1. Visit the [Triangle Test Case Exercise](https://baseinfinity.github.io/triangle-exercise/) page.
2. Read the description of the triangle classification program.
3. Enter your test cases in the provided textarea, one per line, in the format: `side1,side2,side3`
4. Click the "Evaluate Test Cases" button to see your results.
5. Review your score and the detailed feedback to understand which cases you covered and which you missed.

## Local Development

To run this project locally:

1. Clone the repository:
   ```
   git clone https://github.com/baseinfinity/triangle-exercise.git
   ```
2. Navigate to the project directory:
   ```
   cd triangle-exercise
   ```
3. Open `index.html` in your web browser.

## Contributing

Contributions to improve the exercise or add new features are welcome! Please feel free to submit a pull request or open an issue to discuss potential changes.

## Community

Join our [Software Automation Discord Server](https://discord.com/invite/9m4HkejXgs) to discuss this exercise, software testing, and automation with other enthusiasts and professionals!
