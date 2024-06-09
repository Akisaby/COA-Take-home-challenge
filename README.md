# COA-Take-home-challenge
Overview
This project contains solutions for three tasks: an interactive photo gallery, an array manipulation coding challenge, and a string transformation coding challenge.

Table of Contents
- Interactive Photo Gallery: interactive-photo-gallery
- Coding Challenge 1: Array Manipulation
- Coding Challenge 2: String Transformation

Interactive Photo Gallery

Description
Implement an interactive photo gallery based on the provided Figma designs. The gallery should be responsive and work seamlessly on both desktop and mobile devices. Due to time limitations, detailed image interactions were not implemented. Instead, images were simply placed in order.

Features
- Responsive design for desktop and mobile
- Images placed in order
- Note: Detailed image interactions were not implemented due to time limitations.

Coding Challenge 1: Array Manipulation
Problem Statement:
Given an array of integers and a target sum, determine if there exists a contiguous
subarray within the array that sums up to the target. Return true if such a subarray exists,
otherwise return false.
Example:
Input: arr = [4, 2, 7, 1, 9, 5], target = 17
Output: true
Explanation: The subarray [7, 1, 9] sums up to 17, which is equal to the target.
Constraints:
- The array will contain between 1 and 100,000 elements.
- The elements in the array and the target sum will be between -1,000,000,000 and
1,000,000,000.
Expected Time Complexity: O(n), where n is the length of the array.
Expected Space Complexity: O(1).
4.3 Coding Challenge 2: String Transformation
Here's the updated problem statement with real-world word examples:
Problem Statement: Given a string, transform it based on the following rules:
● If the length of the string is divisible by 3, reverse the entire string.
● If the length of the string is divisible by 5, replace each character with its ASCII code.
● If the length of the string is divisible by both 3 and 5 (i.e., divisible by 15), perform
both operations in the order specified above.
Example: Input: "Hamburger"
Output: "regrubmaH"
Explanation: The length of the string is 9, which is divisible by 3 but not by 5 or 15.
Therefore, the string is reversed, resulting in "regrubmaH".
Example: Input: "Pizza"
Output: "80 105 122 122 97"
Explanation: The length of the string is 5, which is divisible by 5 but not by 3 or 15.
Therefore, each character is replaced by its ASCII code, resulting in "80 105 122 122 97".
Example: Input: "Chocolate Chip Cookie"
Output: "eikooCpihCetalocohC"
Explanation: The length of the string is 21, which is divisible by 3 but not by 5 or 15.
Therefore, the string is reversed, resulting in "eikooCpihCetalocohC".
Constraints:
● The string will only contain alphanumeric characters and spaces.
● The length of the string will be between 1 and 1000.
Expected Time Complexity: O(n), where n is the length of the string. Expected Space
Complexity: O(n), where n is the length of the string.
Note: You can assume that the input will always be valid and within the specified
constraints. Your solution should handle all possible cases and return the transformed
string accordingly.
These examples use real-world words related to food to illustrate the transformations
applied based on the divisibility of the string length by 3, 5, and 15