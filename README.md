Download Link: https://assignmentchef.com/product/solved-assignment-6
<br>
1 [25 points]This assignment will give you a chance to perform some simple tasks with pointers. The instructions below are a sequence of tasks that are only loosely related to each other. Start the assignment by creating a .cpp file with an empty main function, then add statements to accomplish each of the tasks listed below. Some of the tasks will only require a single C++ statement, others will require more than one. Make sure that the tasks appear in your code in the same order that they are listed here.No documentation is required for this part of the assignment.Create two integer variables named x and y

Create an int pointer named p1Store the address of x in p1Use only p1 (not x) to set the value of x to 99Using cout and x (not p1), display the value of xUsing cout and the pointer p1 (not x), display the value of xStore the address of y into p1Use only p1 (not y) to set the value of y to -300

Create two new variables: an int named temp, and an int pointer named p2. Make p2 point to x.Use only temp, p1, and p2 (not x or y) to swap the values in x and y (this will take a few statements. Don’t use a swap function)Write a function with the following signature: void noNegatives(int *x). The function should accept the address of an int variable. If the value of this integer is negative then it should set it to zeroInvoke the function twice: once with the address of x as the argument, and once with the address of y. Use x or y for the argument (not p1 or p2)

Use p2 to display the values in x and y (this will require both assignment statements and cout statements). You can use x and y in assignment statements, but not in your cout statement. this should produce the outputx is: 0y is: 99

Create an int array named ‘a’ with two elements. Make p2 point to the first element of a.Use only p2 and x (not a) to initialize the first element of a with the value of x.Use only p2 and y (not a) to initialize the second element of a with the value of y. Leave p2 pointing to the first element of a.

Using cout and p2 only, display the address of the first element in a.Using cout and p2 only, display the address of the second element in a. Leave p2 pointing to the first element of a.Use p1, p2, and temp to swap the values in the two elements of array ‘a’. (first point p1 at a[0], then point p2 at a[1], then do not use “a” again. After this the swapping steps should look very similar to step 10. Don’t use a swap function.)

Display the values of the two elements. (The first element should be 99, the second 0).

Write a function named ‘swap’ that accepts two pointers to integers as arguments, and then swaps the contents of the two integers. Do not use any reference parameters.Invoke your swap function with the addresses of x and y (using the address-of operator), then print their values. (x should be 99, y should be 0).

Invoke your swap function with the address of the two elements in array ‘a’, then print their values. (a[0] should be 0, a[1] should be 99)Assignment 6.2 [20 points]Rewrite your High Scores program so that it uses Dynamic Memory Allocation to create the names and scores arrays.You will only need to make slight modifications to your main function if you wrote your original program correctly using the function signatures required for that assignment.

Your function signatures for this assignment should be exactly the same as the signatures required in the original High Scores assignment.Your modified high scores program should start out by asking the user how many scores will be entered. It should allocate appropriate arrays, and then proceed just like the original High Scores assignment. The output from your program should look approximately like this:How many scores will you enter?: 4

Enter the name for score #1: SuzyEnter the score for score #1: 9900Enter the name for score #2: KimEnter the score for score #2:(###) ###-####Enter the name for score #3: ArmandoEnter the score for score #3: 822Enter the name for score #4: TimEnter the score for score #4: 514Top Scorers:Kim:(###) ###-####Suzy: 9900Armando: 822Tim: 514