

=============
Numbers Again
=============


*************
Numbers Again
*************


---------------------------------------------------------------
asg_a0041 : Number2 - Left Rotate a 5 digit number by n places.
---------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``rotate_numbers()`` which when passed a number and N, rotates the number left by N places.


'''''''
Samples
'''''''
========  ========================================  ==============  =========
  Number  Explanation                               Input              Output
========  ========================================  ==============  =========
       1  Check if function is proper               [12345, 1]          23451
       2  Check if function is proper for negative  [-12345, 1]        -23451
       3  Check if function is proper               [23145, 1]          31452
       4  Check if function is proper               [234567891, 1]  345678912
========  ========================================  ==============  =========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int rotate_left_numbers(int number, int places)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =================================  =========
  Number  Type    Name    Explanation                        Remarks
========  ======  ======  =================================  =========
       1  int     number  Number to be rotated by one place
       2  int     places  Places to rotate.
========  ======  ======  =================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==========================  =========
  Number  Type    Name    Explanation                 Remarks
========  ======  ======  ==========================  =========
       1  int     NA      Rotated number by n places
========  ======  ======  ==========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number to be rotated by one place
	 * int places - Places to rotate.
	 */
	
	int rotate_left_numbers(int number, int places) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int rotate_left_numbers(int number, int places)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------
asg_a0043 : Number2 - Find the length of a number
-------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``numlen()`` which when passed a number returns the number of digits in the number.


'''''''
Samples
'''''''
========  ========================================  =======  ========
  Number  Explanation                               Input      Output
========  ========================================  =======  ========
       1  Check if function is proper               [1234]          4
       2  Check if function is proper for negative  [-1234]         4
       3  Check if function is proper               [0]             0
========  ========================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int numlen(int num)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =============  =========
  Number  Type    Name    Explanation    Remarks
========  ======  ======  =============  =========
       1  int     num     Input number
========  ======  ======  =============  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ======================================  =========
  Number  Type    Name    Explanation                             Remarks
========  ======  ======  ======================================  =========
       1  int     NA      Number of digits in the number passed.
========  ======  ======  ======================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num - Input number
	 */
	
	int numlen(int num) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int numlen(int num)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------
asg_a0864 : Number2 - Write a function to round numbers.
--------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``round_number(double number)`` which takes input a double type number and returns the rounded number.


'''''''
Samples
'''''''
========  ===============================  ========  ========
  Number  Explanation                      Input       Output
========  ===============================  ========  ========
       1  Check if the function is proper  [16.34]         16
       2  Check if the function is proper  [16.57]         17
       3  Check if the function is proper  [-20.51]       -19
========  ===============================  ========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int round_number(double number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =================================  =========
  Number  Type    Name    Explanation                        Remarks
========  ======  ======  =================================  =========
       1  double  number  Input double number to be rounded
========  ======  ======  =================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ====================================================  =========
  Number  Type    Name    Explanation                                           Remarks
========  ======  ======  ====================================================  =========
       1  int     NA      Returns the integer value of the double number input
========  ======  ======  ====================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * double number - Input double number to be rounded
	 */
	
	int round_number(double number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int round_number(double number)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------
asg_a0922 : Number2 - Convert a number to its reverse 123456 --> 654321.
------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``reverse_number()`` which when passed an integer returns the reverse of the integer.


'''''''
Samples
'''''''
========  =========================  ==================  ==================
  Number  Explanation                Input               Output
========  =========================  ==================  ==================
       1  Check for a general case.  [1, 2, 3, 4, 5, 6]  [6, 5, 4, 3, 2, 1]
========  =========================  ==================  ==================


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int reverse_number (int input)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==============================  =========
  Number  Type    Name    Explanation                     Remarks
========  ======  ======  ==============================  =========
       1  int     input   Integer number to be reversed.
========  ======  ======  ==============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===========================  =========
  Number  Type    Name    Explanation                  Remarks
========  ======  ======  ===========================  =========
       1  int     NA      Return the reversed number.
========  ======  ======  ===========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int input - Integer number to be reversed.
	 */
	
	int reverse_number (int input) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int reverse_number (int input)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------
asg_a2245 : Number2 - Sum of multiples of 3 or 5 below N.
---------------------------------------------------------


'''''''''''
Description
'''''''''''

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Write a function ``sum_all_multiples()`` which returns the sum of all the multiples of 3 and 5 below N. N will be passed as an argument.


'''''''
Samples
'''''''
========  ============================  =======  ========
  Number  Explanation                     Input    Output
========  ============================  =======  ========
       1  Check if function is correct       10        23
========  ============================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int sum_all_multiples()``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ================================================  =========
  Number  Type    Name    Explanation                                       Remarks
========  ======  ======  ================================================  =========
       1  int     N       Number till where we have to find the multiples.
========  ======  ======  ================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ============================  =========
  Number  Type    Name    Explanation                   Remarks
========  ======  ======  ============================  =========
       1  int     NA      The calculated return value.
========  ======  ======  ============================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int N - Number till where we have to find the multiples.
	 */
	
	int sum_all_multiples() {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int sum_all_multiples()
	}

.. raw:: latex

    \clearpage


----------------------------------------------------------
asg_a0993 : Number2 - Check if a number is a prime number.
----------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_prime(int number)`` which takes input a number and checks if the number is prime or not.


'''''''
Samples
'''''''
========  ===============================  =======  ========
  Number  Explanation                        Input    Output
========  ===============================  =======  ========
       1  Check if the function is proper        5         0
       2  Check if the function is proper       12        -1
========  ===============================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_prime(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     number  number to be worked upon.
========  ======  ======  =========================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =========================================  =========
  Number  Type    Name    Explanation                                Remarks
========  ======  ======  =========================================  =========
       1  int     NA      0 if the number is prime, else return -1.
========  ======  ======  =========================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - number to be worked upon.
	 */
	
	int is_prime(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_prime(int number)
	}

.. raw:: latex

    \clearpage


----------------------------------------------
asg_a0890 : Number2 - Find out Nth ugly number
----------------------------------------------


'''''''''''
Description
'''''''''''

Ugly numbers are numbers whose only prime factors are 2, 3 or 5. The sequence 1, 2, 3, 4, 5, 6, 8, 9, 10, 12, 15, ...  shows the first 11 ugly numbers.  By convention, 1 is included.  Write a function ``find_ugly(int nth)`` to find and return the Nth ugly number. The function takes input the nth place which is to be found for ugly number.


'''''''
Samples
'''''''
========  ===============================  =======  ========
  Number  Explanation                      Input      Output
========  ===============================  =======  ========
       1  Check if the function is proper  [3]             5
       2  Check if the function is proper  [12]            0
========  ===============================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_ugly(int nth)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==================================================  =========
  Number  Type    Name    Explanation                                         Remarks
========  ======  ======  ==================================================  =========
       1  int     nth     nth place for which the ugly number is to be found
========  ======  ======  ==================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===========================  =========
  Number  Type    Name    Explanation                  Remarks
========  ======  ======  ===========================  =========
       1  int     NA      Returns the nth ugly number
========  ======  ======  ===========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int nth - nth place for which the ugly number is to be found
	 */
	
	int find_ugly(int nth) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_ugly(int nth)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------------------------------
asg_a0020 : Number2 - Make the maximum possible number from the digits of a number.
-----------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``make_maximum_number()`` which when passed a number, uses its digits to make another number. The new number should be the maximum possible number which can be made from those digits. Note that the digits can be repeated in the input number.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                  Input      Output
========  ===========================  =======  ========
       1  Check if function is proper  [12309]     93210
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int make_maximum_number(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =============================  =========
  Number  Type    Name    Explanation                    Remarks
========  ======  ======  =============================  =========
       2  int     number  The number to be worked upon.
========  ======  ======  =============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===============  =========
  Number  Type    Name    Explanation      Remarks
========  ======  ======  ===============  =========
       1  int     NA      The new number.
========  ======  ======  ===============  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - The number to be worked upon.
	 */
	
	int make_maximum_number(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int make_maximum_number(int number)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------
asg_a0026 : Number2 - Generate numbers in an array.
---------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``generate_numbers()`` which when passed a number and an array, fills the array upto that index. For filling the array it uses the index, adds the digits of the index, squares the result, multiplies the number by 10, mods the number by the index and then stores it.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                  Input    Output
========  ===========================  =======  ========
       1  Check if function is proper  NA       NA
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``void generate_numbers(int *array, int index, int length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ===============================================================  =========
  Number  Type    Name    Explanation                                                      Remarks
========  ======  ======  ===============================================================  =========
       2  int *   array   The array to be filled.
       2  int     index   The index of the array till where the array needs to be filled.
       2  int     length  The length of the array passed.
========  ======  ======  ===============================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===============  =========
  Number  Type    Name    Explanation      Remarks
========  ======  ======  ===============  =========
       1  int     NA      The new number.
========  ======  ======  ===============  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int * array - The array to be filled.
	 * int index - The index of the array till where the array needs to be filled.
	 * int length - The length of the array passed.
	 */
	
	void generate_numbers(int *array, int index, int length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void generate_numbers(int *array, int index, int length)
	}

.. raw:: latex

    \clearpage
