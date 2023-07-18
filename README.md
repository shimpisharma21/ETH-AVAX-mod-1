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
https://www.loom.com/share/afd49f8891734d338f1fe06f8cb77e28?sid=c40149bb-57cf-4f59-8ecc-8e5a62339a4d
