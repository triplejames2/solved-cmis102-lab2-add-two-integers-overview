Download Link: https://assignmentchef.com/product/solved-cmis102-lab2-add-two-integers-overview
<br>
Week 2

This hands-on lab allows you to follow and experiment with the critical steps of developing a program including the program description, analysis, test plan, design, and implementation with C code.

Program Description

This program will sum two integer numbers to yield a third integer number.

Once the calculations are made the results of all the numbers will be printed to the output screen.

Analysis

We will use sequential programming statements. We will define 3 integer numbers: x, y, z z will store the sum of x and y.

<strong> </strong>Test Plan

To understand this program the following input numbers could be used for testing:

x = 10 y = 20

z = x + y = 10 + 20 = 30

In table format the following results are expected:

<table width="0">

 <tbody>

  <tr>

   <td width="73"><strong>Run # </strong></td>

   <td width="102"><strong>Input x </strong></td>

   <td width="108"><strong>Input y </strong></td>

   <td width="132"><strong>Expected Output </strong></td>

  </tr>

  <tr>

   <td width="73">1</td>

   <td width="102">10</td>

   <td width="108">20</td>

   <td width="132">30</td>

  </tr>

  <tr>

   <td width="73">2</td>

   <td width="102">0</td>

   <td width="108">0</td>

   <td width="132">0</td>

  </tr>

  <tr>

   <td width="73">3</td>

   <td width="102">124</td>

   <td width="108">356</td>

   <td width="132">480</td>

  </tr>

  <tr>

   <td width="73">4</td>

   <td width="102">-30</td>

   <td width="108">-90</td>

   <td width="132">-120</td>

  </tr>

 </tbody>

</table>

<h1>Design using Pseudocode</h1>

// This program will sum two integer numbers to yield a third integer number.  // Later, it will divide two float numbers to yield a third float number.

// Declare variables Declare x, y, z as Integer




// Set values of Integers

Set x=10

Set y=20

Set z= x + y

// Print x, y, z

Print x,y,z

<h1>C  Code</h1>

The following is the C Code that will compile in execute in the online compilers.

// C code

// This program will sum two integer numbers to yield a third integer number.

// Developer: Faculty CMIS102

// Date: Jan 31, XXXX




#include &lt;stdio.h&gt; int main ()

{

/* variable definition: */   int x, y, z;




/* variable initialization */   x = 10;   y = 20;     z = x + y;

printf(“Integers (x,y) and sum (z) are : %d,%d,%d 
”, x,y,z);      return 0;

}




Results from running the programming at repl.it:

<strong>              </strong>Learning Exercises for you to complete

<ol>

 <li>Change the code to include your name, the name of this class, and the name of this project as the initial part of the output.</li>

 <li>Demonstrate you successfully followed the steps in this lab by preparing screen captures of you running the lab as specified in the Instructions above.</li>

 <li>(Tests: x*y): Prepare a new test table with at least 3 distinct test cases listing input and expected output for the product of two integers.</li>

 <li>(x*y): Change the C code to calculate the product of two integers as opposed to the sum of two integers. Then run the new code. Support your experimentation with a screen capture of the code and a screen capture of the successful execution of the new code. Include screen shots of the executions of all test table values working properly.</li>

 <li>(Tests: x/y): Prepare a new test table with at least 3 distinct test cases listing input and expected output for the quotient of two floats.</li>

 <li>(float x/y): Change the C code to calculate the quotient (i.e. x/y) of two floats (e.g. 2.3/1.5).</li>

</ol>

Hint: Use float variable types as opposed to integers.

What happens if the denominator is 0.0?

Support your experimentation with screen captures of executions the new code.




<ol start="7">

 <li>(int vs float): What happens if x, y, and z are declared as int and the operation is division?</li>

</ol>