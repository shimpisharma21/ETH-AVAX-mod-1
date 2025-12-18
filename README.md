# IITJEEEligibility Contract
This contract provides a set of functions to check the eligibility criteria for the IIT JEE (Indian Institutes of Technology Joint Entrance Examination). It verifies the age and marks percentage of a student and determines whether they are eligible to appear for the exam.
### Requirements
Solidity version 0.8.0 or higher
### Usage
Interact with the contract using the following functions:

#### checkAgeEligibility(uint256 age)
This function checks if the given age parameter is within the required range of 17 to 25.

Returns:

true if the age is within the eligible range.
Throws an error message if the age is outside the eligible range.

#### assertMarksEligibility(uint256 marksPercentage)

This function uses the assert statement to verify if the given marksPercentage parameter is equal to or greater than 75.

#### checkEligibility(uint256 age, uint256 marksPercentage)
This function combines the age and marks eligibility checks and reverts with an error message if any of the criteria are not met.

### License
// SPDX-License-Identifier: MIT

### walkthrough the code on loom.
https://www.loom.com/share/b86f337e59224ed5963f1d97d6de33e5?sid=2d3af7bb-d317-4f9c-bc32-2c0b01388397


just to check any changes?
wow i love this finally i have successfully pushed my changes on github😎🙈😝🏆