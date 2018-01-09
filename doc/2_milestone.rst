

====================
Decision Making in C
====================


***************
Decision Making
***************


-------------------------------------
asg_a0128 : Decision - Check for zero
-------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_zero()`` which checks if the number is zero or not.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                  Input    Output
========  ===========================  =======  ========
       1  Check if function is proper  [0]      True
       2  Check if function is proper  [10]     False
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_zero(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     number  Number to be worked upon.
========  ======  ======  =========================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =========================================  =========
  Number  Type    Name    Explanation                                Remarks
========  ======  ======  =========================================  =========
       1  int     NA      0  if the number is zero, else return -1.
========  ======  ======  =========================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number to be worked upon.
	 */
	
	int is_zero(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_zero(int number)
	}

.. raw:: latex

    \clearpage


------------------------------------------------
asg_a0940 : Decision - Check if a number is odd.
------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``check_if_odd()`` to check if a number is odd or no. Return -1 if even, else return 0.


'''''''
Samples
'''''''
========  ========================  =======  ========
  Number  Explanation                 Input    Output
========  ========================  =======  ========
       1  Check for a odd number.         5         0
       2  Check for a even number.        6        -1
========  ========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int check_if_odd(int num)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     num     The number to be checked.
========  ======  ======  =========================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===============================  =========
  Number  Type    Name    Explanation                      Remarks
========  ======  ======  ===============================  =========
       1  int     NA      0 if the number is odd, else -1
========  ======  ======  ===============================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num - The number to be checked.
	 */
	
	int check_if_odd(int num) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int check_if_odd(int num)
	}

.. raw:: latex

    \clearpage


------------------------------------------------
asg_a0941 : Decision - Check if a number is even
------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_even()`` to check if a number is even or no. Return 0 if the number is even, else return -1.


'''''''
Samples
'''''''
========  =============  =======================  ========
  Number  Explanation    Input                      Output
========  =============  =======================  ========
       1                 Check for even numbers.         4
       2                 Check for odd numbers.          5
========  =============  =======================  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_even(int num)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     num     The number to be checked.
========  ======  ======  =========================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =====================  =========
  Number  Type    Name    Explanation            Remarks
========  ======  ======  =====================  =========
       1  int     NA      0 if even, -1 if odd.
========  ======  ======  =====================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num - The number to be checked.
	 */
	
	int is_even(int num) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_even(int num)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------
asg_a2202 : Decision - Find maximum of two numbers.
---------------------------------------------------


'''''''''''
Description
'''''''''''

Define a function ``mymax()`` that takes two numbers as arguments and returns the largest of them. Use the if-then-else construct available in your language.


'''''''
Samples
'''''''
========  ========================================================  =======  ========
  Number  Explanation                                               Input      Output
========  ========================================================  =======  ========
       1  Test if the function can find the maximum.                [5, 6]          6
       2  Test the function behaviour when same values are passed.  [5, 5]          5
========  ========================================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int mymax(int num1, int num2)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==================  =========
  Number  Type    Name    Explanation         Remarks
========  ======  ======  ==================  =========
       1  int     num1    The first number.
       2  int     num2    The second number.
========  ======  ======  ==================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==================  =========
  Number  Type    Name    Explanation         Remarks
========  ======  ======  ==================  =========
       1  int     NA      The larger number.
========  ======  ======  ==================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num1 - The first number.
	 * int num2 - The second number.
	 */
	
	int mymax(int num1, int num2) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int mymax(int num1, int num2)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------
asg_a2203 : Decision - Find the maximum of three numbers.
---------------------------------------------------------


'''''''''''
Description
'''''''''''




'''''''
Samples
'''''''
========  ===========================  ============  ========
  Number  Explanation                  Input           Output
========  ===========================  ============  ========
       1  First input is maximum.      [7, 6, 5]            7
       2  Middle one is the maximum.   [5, 7, 6]            7
       3  Last on is the maximum.      [5, 6, 7]            7
       4  Check for negative numbers.  [-5, -6, -7]        -5
       5  All equal.                   [5, 5, 5]            5
========  ===========================  ============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int max_of_three(int a, int b, int c)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =============  =========
  Number  Type    Name    Explanation    Remarks
========  ======  ======  =============  =========
       1  int     a       First number
       1  int     b       Second number
       1  int     c       Third number
========  ======  ======  =============  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =====================================  =========
  Number  Type    Name    Explanation                            Remarks
========  ======  ======  =====================================  =========
       1  int     NA      The number which is maximum of three.
========  ======  ======  =====================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int a - First number
	 * int b - Second number
	 * int c - Third number
	 */
	
	int max_of_three(int a, int b, int c) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int max_of_three(int a, int b, int c)
	}

.. raw:: latex

    \clearpage


------------------------------------------------
asg_a0129 : Decision - Find maximum in 4 numbers
------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_maximum_in_4()`` which finds the maximum out of the 4 numbers passed to it.


'''''''
Samples
'''''''
========  ===========================  ===================  ========
  Number  Explanation                  Input                  Output
========  ===========================  ===================  ========
       1  Check if function is proper  [20, 10, 5, 21]            21
       2  Check if function is proper  [20, 10, 5, -21]           20
       3  Check if function is proper  [-20, -10, -5, -21]        -5
========  ===========================  ===================  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_maximum_in_4 (int num1, int num2, int num3, int num4)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =============  =========
  Number  Type    Name    Explanation    Remarks
========  ======  ======  =============  =========
       1  int     num1    First number
       2  int     num2    Second number
       3  int     num3    Third  number
       4  int     num4    Fourth number
========  ======  ======  =============  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =======================================  =========
  Number  Type    Name    Explanation                              Remarks
========  ======  ======  =======================================  =========
       1  int     NA      The maximum of the four numbers passed.
========  ======  ======  =======================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num1 - First number
	 * int num2 - Second number
	 * int num3 - Third  number
	 * int num4 - Fourth number
	 */
	
	int find_maximum_in_4 (int num1, int num2, int num3, int num4) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_maximum_in_4 (int num1, int num2, int num3, int num4)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------
asg_a0124 : Decision - Find minimum among 3 values.
---------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``my_minimum()`` which when passed any three numbers returns the one which is the minimum.


'''''''
Samples
'''''''
========  ===========================  ============  ========
  Number  Explanation                  Input           Output
========  ===========================  ============  ========
       1  Check if function is proper  [10, 5, 20]          5
       2  Check if function is proper  [10, -5, 20]        -5
       3  Check if function is proper  [0, 0, 0]            0
========  ===========================  ============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int my_minimum(int num1, int num2, int num3)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==================  =========
  Number  Type    Name    Explanation         Remarks
========  ======  ======  ==================  =========
       1  int     num1    The first number.
       2  int     num2    The second number.
       3  int     num3    The third number.
========  ======  ======  ==================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ============================  =========
  Number  Type    Name    Explanation                   Remarks
========  ======  ======  ============================  =========
       1  int     NA      The number which is minimum.
========  ======  ======  ============================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num1 - The first number.
	 * int num2 - The second number.
	 * int num3 - The third number.
	 */
	
	int my_minimum(int num1, int num2, int num3) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int my_minimum(int num1, int num2, int num3)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------
asg_a0908 : Decision - Check if number is multiple of 3
-------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_multiple_of_3()`` to check whether a given number is a multiple of 3.


'''''''
Samples
'''''''
========  =============  =======  ========
Number    Explanation    Input    Output
========  =============  =======  ========
========  =============  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_multiple_of_3(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================  =========
  Number  Type    Name    Explanation            Remarks
========  ======  ======  =====================  =========
       1  int     number  Number to be checked.
========  ======  ======  =====================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==========================================================  =========
  Number  Type    Name    Explanation                                                 Remarks
========  ======  ======  ==========================================================  =========
       1  int     NA      Return 0 if the number is a multiple of 3, else return -1.
========  ======  ======  ==========================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number to be checked.
	 */
	
	int is_multiple_of_3(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_multiple_of_3(int number)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------------------------------------
asg_a0853 : Decision - Write a function to check if a given year is a leap year or not?
---------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_leap_year(int year)`` to check if the valid year passed to the function is a leap year or not. Leap year is a year which has 366 days instead of 365 days in a year. The function should return True if the year is a leap year, else it should return False. In case of invalid input, it should return False.


'''''''
Samples
'''''''
========  ===============================  =======  ========
  Number  Explanation                      Input    Output
========  ===============================  =======  ========
       1  Check if the function is proper  [2016]   True
       2  Check if the function is proper  [-2016]  False
       3  Check if the function is proper  [2017]   False
========  ===============================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_leap_year(int year)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ========================================  =========
  Number  Type    Name    Explanation                               Remarks
========  ======  ======  ========================================  =========
       1  int     year    Input year to be validated for Leap Year
========  ======  ======  ========================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =============================================  =========
  Number  Type    Name    Explanation                                    Remarks
========  ======  ======  =============================================  =========
       1  int     NA      0 if the year is a leap year, else return -1.
========  ======  ======  =============================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int year - Input year to be validated for Leap Year
	 */
	
	int is_leap_year(int year) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_leap_year(int year)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------
asg_a0122 : Decision - Find if profit was made in a sale.
---------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_profit()`` which when passed the Selling Price and Cost Price, returns if there was a profit made in the sale.


'''''''
Samples
'''''''
========  ===========================  ==========  ========
  Number  Explanation                  Input         Output
========  ===========================  ==========  ========
       1  Check if function is proper  [200, 100]         1
========  ===========================  ==========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_profit(float selling_price, float cost_price)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  =============  =============================  =========
  Number  Type    Name           Explanation                    Remarks
========  ======  =============  =============================  =========
       1  float   selling_price  Selling price of the article.
       2  float   cost_price     Cost price of the article.
========  ======  =============  =============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =============================================================================================================================  =========
  Number  Type    Name    Explanation                                                                                                                    Remarks
========  ======  ======  =============================================================================================================================  =========
       1  int     NA      Return value based on the result obtained. If there is a profit return >0, for no profit no loss return 0, for loss return -1
========  ======  ======  =============================================================================================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * float selling_price - Selling price of the article.
	 * float cost_price - Cost price of the article.
	 */
	
	int is_profit(float selling_price, float cost_price) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_profit(float selling_price, float cost_price)
	}

.. raw:: latex

    \clearpage


----------------------------------------------------------------
asg_a0944 : Decision - Count the odd digits in a 5 digit number.
----------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``count_odd_digits()``. Return the number of digits which are odd in a 5 digit number.


'''''''
Samples
'''''''
========  ======================================  =======  ========
  Number  Explanation                               Input    Output
========  ======================================  =======  ========
       1  Check if the function works correctly.    12345         3
       2  Check if the function works correctly.    13579         5
       3  Check if the function works correctly.    24680         0
========  ======================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int count_odd_digits(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  int     number  Number to be checked for odd digits.
========  ======  ======  ====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =====================  =========
  Number  Type    Name    Explanation            Remarks
========  ======  ======  =====================  =========
       1  int     NA      Number of odd digits.
========  ======  ======  =====================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number to be checked for odd digits.
	 */
	
	int count_odd_digits(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int count_odd_digits(int number)
	}

.. raw:: latex

    \clearpage


-------------------------------------
asg_a0130 : Decision - Find the grade
-------------------------------------


'''''''''''
Description
'''''''''''


Write a function ``find_grade()`` which will take marks as input and return
a number based on the grade obtained.

Grade can be calculated as follows

Grade 1     - above 80 

Grade 2     - above 60 less than equal to 80

Grade 3     - above 40 less than equal to 60

Grade 4     - above 20 less than equal to 40

Grade 5     - above 00 less than equal to 20

If the marks is more than 100 or is invalid, return -1.



'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                  Input      Output
========  ===========================  =======  ========
       1  Check if function is proper  [60]            3
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_grade(int marks)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  =======  ======  ===============================================  =========
  Number  Type     Name    Explanation                                      Remarks
========  =======  ======  ===============================================  =========
       1  integer  marks   The marks of which the grade needs to be found.
========  =======  ======  ===============================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =============================================================  =========
  Number  Type    Name    Explanation                                                    Remarks
========  ======  ======  =============================================================  =========
       1  int     NA      The Grade to be returned based on the calculations mentioned.
========  ======  ======  =============================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * integer marks - The marks of which the grade needs to be found.
	 */
	
	int find_grade(int marks) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_grade(int marks)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------------
asg_a0945 : Decision - Check even digits in a 5 digit number.
-------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``count_even_digits()`` which will count the number of even digits in a 5 digit number.


'''''''
Samples
'''''''
========  ======================================  =======  ========
  Number  Explanation                               Input    Output
========  ======================================  =======  ========
       1  Check if the function works correctly.    12345         2
       2  Check if the function works correctly.    17395         0
========  ======================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int count_even_digits(int num)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  int     num     The number to check for even digits.
========  ======  ======  ====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ========================================  =========
  Number  Type    Name    Explanation                               Remarks
========  ======  ======  ========================================  =========
       1  int     NA      The number of even digits in the number.
========  ======  ======  ========================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num - The number to check for even digits.
	 */
	
	int count_even_digits(int num) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int count_even_digits(int num)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------
asg_a0044 : Decision - Check palindrome of a 5 digit number.
------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_palindrome_number()`` which when passed a number checks if the number is palindrome or not and returns 0 or -1.


'''''''
Samples
'''''''
========  ========================================  ========  ========
  Number  Explanation                               Input       Output
========  ========================================  ========  ========
       1  Check if function is proper               [12321]          0
       2  Check if function is proper for negative  [-12321]         0
       3  Check if function is proper               [12345]         -1
========  ========================================  ========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_palindrome_number(int num)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  int     num     Input number to check for palindrome
========  ======  ======  ====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ============================  =========
  Number  Type    Name    Explanation                   Remarks
========  ======  ======  ============================  =========
       1  int     NA      0 for True and -1 for False.
========  ======  ======  ============================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num - Input number to check for palindrome
	 */
	
	int is_palindrome_number(int num) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_palindrome_number(int num)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------------
asg_a2101 : Decision - Product of digits of a 5 digit number.
-------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``product_of_5_digits()`` which returns the products of the digits passed to the function. In case any digit is zero then skip that digit - no need to multiply zero to the product.
For negative numbers the product should be negative.
For 0 the product should be 0.
For numbers with digits less than 5 return -1.


'''''''
Samples
'''''''
========  ============================================================================  =======  ========
  Number  Explanation                                                                     Input    Output
========  ============================================================================  =======  ========
       1  Check if function is proper                                                     12345       120
       2  Check if function is proper for negative input                                 -12345      -120
       3  Check if function is proper for input with zero                                     0         0
       4  Check if function is proper for input with zeros in between.                    12031         6
       5  Check if function is proper for input with zeros in between and is negative.   -12031        -6
       6  Check if function is proper for input less than 5 digits.                        2031        -1
========  ============================================================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int product_of_5_digits(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =========================================  =========
  Number  Type    Name    Explanation                                Remarks
========  ======  ======  =========================================  =========
       1  int     number  Number whose digits are to be multiplied.
========  ======  ======  =========================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==========================  =========
  Number  Type    Name    Explanation                 Remarks
========  ======  ======  ==========================  =========
       1  int     NA      Product of all the digits.
========  ======  ======  ==========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number whose digits are to be multiplied.
	 */
	
	int product_of_5_digits(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int product_of_5_digits(int number)
	}

.. raw:: latex

    \clearpage
