# Student Grade Calculator

This program calculates a student's grade based on their marks input by the user. It uses a series of conditions to determine the grade and provides an output accordingly.

## How to Use

1. **Run the Program:**
   - Open the JavaScript file (`gradeCalculator.js`) in a JavaScript environment such as a browser console or a Node.js environment.

2. **Input Student Marks:**
   - When prompted, enter the student's marks. The marks should be a numerical value between 0 and 100.

3. **View the Grade:**
   - The program will calculate the grade based on the provided marks and print it to the console.

4. **Handle Invalid Input:**
   - If the input provided by the user is not a valid number or falls outside the range of 0 to 100, an error message will be displayed, prompting the user to input a valid number within the specified range.

## Function Description

The program defines a JavaScript function `calculateGrade(marks)` that takes the student's marks as input and returns the corresponding grade based on the following criteria:

- 'A' if marks are greater than 79.
- 'B' if marks are between 60 and 79 (inclusive).
- 'C' if marks are between 50 and 59 (inclusive).
- 'D' if marks are between 40 and 49 (inclusive).
- 'E' if marks are less than 40.

## Input Validation

The program ensures that the input provided by the user is a valid number and falls within the range of 0 to 100. It uses the `isNaN` function and logical operators to validate the input.



