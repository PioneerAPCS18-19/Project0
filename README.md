# Project 0

The U.S. post office has rules about mailing packages. A package cannot be mailed first class if the sum of its length and girth is greater than 100 inches, or if the package weighs more than 70 pounds. The girth is the perimeter around the height and width, where the length is defined as the longest of the three dimensions.

This project is intended to be the wrap up of key topics learned: basic class design and functionality, methods (creating and calling--within and outside of class), if-else statements with boolean expressions, random numbers, and robust program testing.

## Your assignment

Write a program that randomly generates a value for the weight of the package (between 0 and 140) and the three dimensions of the package (between 5 and 60). The program should determine the longest dimension of the package, calculate the girth, and consider the weight. The program should then print out **one** of the following messages about this package:

**Package is too large and too heavy.**

**Package is too large.**

**Package is too heavy.**

**Package is acceptable.**

### Sample Outputs

```
Dimensions: 10, 25, 31
Weight: 71

Package is too large and too heavy.
```

```
Dimensions: 10, 20, 29
Weight: 100

Package is too heavy.
```

```
Dimensions: 34, 12, 57
Weight: 10

Package is too large.
```

```
Dimensions: 7, 10, 19
Weight: 55

Package is acceptable.
```

### Class Design

In your team you will be required to map out your class design and present your proposal to Mr. King before you start any coding. These are the major parts that must be included:

1. Classes you will make.
2. Instance variables you will have.
3. Constructor(s) you will have.
4. Methods you will make.

## Project Rubric

| Scoring Rubric | 6                                          | 4         | 1       |
| -------------- |------------------------------------------- | --------- |-------- |
| Code Style     | Good indentation and braces; easy to read. | Pretty easy to read, occasional error with indentation or braces, comments lacking. | Not easy to read, style conventions are not followed. |
| Functionality  | Program compiles and executes according to specifications. | Program compiles, but a few details of the specification have not been met. | Program does not compile and/or does not achieve desired results according to specifications. |
| Robustness     | Edge cases are accounted for; no unexpected execution (negative length/weight, etc.). | Not all edge cases are accounted for, but no major consequences result. | None or very few of the edge cases have been considered and cause issues with the program. |
| Collaboration  | All teams members contribute code to the project and work well as a team. | All team members contribute code, but distribution may be uneven and/or team members have trouble agreeing on ideas. | Distribution of work is severely uneven and/or team members struggle to agree on ideas. |

**All team members should be working on the code, not just watching one person code.**

**Codeshare.io is an online editor that everyone can edit at the same time like Goolge Docs. Github is a good place to keep "master" files for people to edit, although it is not a live editor like Codeshare or Google Docs.**

## Submission

Please have Mr. King run your code before turning it in. Make sure you have tested it thoroughly (no dimensions or weight should be 0).

At the top of your Runner class file put the team members' first and last names and give a brief explanation of what they did to contribute to the project and code.

Please have **ONE** team member submit the project to Google Classroom.

