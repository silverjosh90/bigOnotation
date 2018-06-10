# **Learning Big O notation**

## **What is big O**

Big O is a way of measuring run-times. It is extremely important when evaluating the practicality and usefulness of an algorithms.

Important Caveat - Run times are measured in worse case scenario.


#### O(n) - Complexity grows linearly with the size of the input.
* Example - Given an unordered list of students, count the number of names that begin with the letter J.
  * Why is this O(n) ?
      * To solve this problem, every single name must be looked at. So if there are 10 students than this problem requires 10 steps, just as if there are 25 students it would require 25 steps. The required number of steps in this problem is equal to the size of the input.

#### O(n<sup>2</sup>) - Complexity grows exponentially with the size of the input.
* Example - Given an unordered list of students, count the number of students who have the same name as them.
  * Why is this O(n<sup>2</sup>) ?
      * This problem requires significantly more steps than the previous. In order to solve this, one must go through each name and then compare that to every other name to find a duplicate. Therefore for every extra student, the solution requires n (number of students in the list) extra steps.
