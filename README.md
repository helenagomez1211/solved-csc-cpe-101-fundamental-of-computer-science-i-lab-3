Download Link: https://assignmentchef.com/product/solved-csc-cpe-101-fundamental-of-computer-science-i-lab-3
<br>
This lab requires the implementation of functions that use boolean logic and functions that use conditional (if) statements.

Download lab3 files from PolyLearn in your CPE101Lab3 directory. These files are <strong>logical_tests.py</strong> and <strong>conditional_tests.py</strong> (corresponding to the different parts of the lab).

<h1>1)    Boolean Logic</h1>

Create a file named <strong>logic.py</strong>. This part of the lab requires that you implement and test multiple functions that compute Boolean values (similar to is_positive from the previous lab). You should develop these functions and their tests one at a time. The function implementations must be placed in <strong>logic.py</strong>. The test cases will be placed in the provided <strong>logical_tests.py</strong>.

You <strong>must</strong> write each of the following functions <strong>without</strong> using any sort of conditional (if) statement.

You must provide at least <strong>three test cases</strong> for each of these functions though you should really provide enough test cases to ensure that the function works even for edge cases. This part will be executed with: <strong>python3 logical_tests.py</strong>

<h2>is_even</h2>

Write a function, named is_even, that takes a single argument assumed to be an integer and that returns True when the integer is even.

There are many ways that one can implement this function; as one example, you should explore the remainder/modulus operator (%).

<h2>in_an_interval</h2>

Write a function, named in_an_interval, that takes a single number argument and returns True when the argument falls in one of the following intervals (recall that a square bracket indicates inclusivity whereas a parenthesis indicates exclusivity; e.g., the interval     [-2,9) includes -2 but not 9). The intervals are [-2,9), (22,42), (12, 20], and [120,127].

This function is meant as an exercise without any clear real-world analog. Write test case for the following values: -10, 0, 9, 20, 122, 127.




<h1>2)    Functions with If Statements</h1>

This part of the lab is similar to the previous part, but the functions for this part will use conditional (if) statements.

In the conditional directory create a file named <strong>conditional.py</strong>. Place your test cases in the provided conditional_tests.py file.

You must provide at least two test cases for each of these functions, but you should really provide enough test cases to ensure that every path through the function is properly tested. This part will be executed with: <strong>python3 conditional_tests.py</strong>

<h2>max_101</h2>

Write a function, named <strong>max_101</strong>, which takes two numbers as arguments and returns the larger of the two values. (Note, this function is actually already provided in Python as max. Do not use the provided function; reason through the logic yourself).

<h2>max_of_three</h2>

Write a function, named <strong>max_of_three</strong>, which takes three arguments of type float and returns the largest of the three values. You should write this using if statements for the practice, but give consideration to how you might write this using the max_101 function above. (Again, do not use the built-in max function.)

<h2>rental_late_fee</h2>

Write a function, named <strong>rental_late_fee</strong>, which takes a single argument representing the number of days late a rental item is returned. This function will return the number of dollars (represented as an integer in this example) for the assessed late fee as defined by the following table.

<table width="83">

 <tbody>

  <tr>

   <td width="53">Days</td>

   <td width="29">Fee</td>

  </tr>

  <tr>

   <td width="53">≤ 0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="53">≤ 9</td>

   <td width="29">5</td>

  </tr>

  <tr>

   <td width="53">≤ 15</td>

   <td width="29">7</td>

  </tr>

  <tr>

   <td width="53">≤ 24</td>

   <td width="29">19</td>

  </tr>

  <tr>

   <td width="53">&gt; 24</td>

   <td width="29">100</td>

  </tr>

 </tbody>

</table>




<strong>Demo Only</strong>: Demo your work and submit .py files to the PolyLearn.