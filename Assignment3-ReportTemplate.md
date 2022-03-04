**SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report #3 – Code Coverage, Adequacy Criteria and Test Case Correlation**

| Group \#:42      |     |
| -------------- | --- |
| Student Names: | Carl Lyss    |
|                | Bhavdeep Purba     |
|                | Mohammadreza Osouli     |
|                | Mohamed Mansour     |

(Note that some labs require individual reports while others require one report
for each group. Please see each lab document for details.)

# 1 Introduction

Text…

# 2 Manual data-flow coverage calculations for X and Y methods

### CalculateColumnTotal data-flow coverage

![DU-Pairs](https://user-images.githubusercontent.com/6359905/156854472-f15f3298-e282-4f25-9561-7c5fa7c52006.jpg)

| Variable | Def | dcu(v,n) | dpu(v,n)        |
| -------- | --- | -------- | --------------- |
| data     |  1  | {3, 5}   | {(2,3), (2,10)} |
| column   |  1  | {5}      | {}              |
| total    |  3  | {7, 9}   | {}              |
| total    |  7  | {7, 9}   | {}              |
| rowCount |  3  | {4}      | {}              |
| r        |  3  | {5, 8}   | {(4,5), (4,9)}  |
| r        |  8  | {5, 8}   | {(4,5), (4,9)}  |
| n        |  5  | {7}      | {(6,7), (6,8)}  |

### Range.combine data-flow coverage
![DU-Pairs]()

| Variable | Def | dcu(v,n) | dpu(v,n)        |
| -------- | --- | -------- | --------------- |
| range1   |  1  | {5,6,7}  | {(2,3), (2,4)}  |
| range2   |  1  | {3,6,7}  | {(4,5), (4,6)}  |
| l        |  6  | {8}      | {}              |
| u        |  7  | {8}      | {}              |

# 3 A detailed description of the testing strategy for the new unit test

Text…

# 4 A high level description of five selected test cases you have designed using coverage information, and how they have increased code coverage

Text…

# 5 A detailed report of the coverage achieved of each class and method (a screen shot from the code cover results in green and red color would suffice)

Text…

# 6 Pros and Cons of coverage tools used and Metrics you report

Text…

# 7 A comparison on the advantages and disadvantages of requirements-based test generation and coverage-based test generation.

Text…

# 8 A discussion on how the team work/effort was divided and managed

Text…

# 9 Any difficulties encountered, challenges overcome, and lessons learned from performing the lab

Text…

# 10 Comments/feedback on the lab itself

Text…
