

======
Arrays
======


******
Arrays
******


-------------------------------------------------------------------------
asg_a0650 : Array - Find the sum of all the elements stored in the array?
-------------------------------------------------------------------------


'''''''''''
Description
'''''''''''




'''''''
Samples
'''''''
========  =========================  ===============  ========
  Number  Explanation                Input              Output
========  =========================  ===============  ========
       1  Check for a general case.  [1, 2, 3, 4, 5]        15
========  =========================  ===============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int sum_of_all_elements(int *array, int length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ===========================  =========
  Number  Type    Name    Explanation                  Remarks
========  ======  ======  ===========================  =========
       1  int*    array   Array to be worked upon.
       2  int     length  Length of the passed array.
========  ======  ======  ===========================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ========================  =========
  Number  Type    Name    Explanation               Remarks
========  ======  ======  ========================  =========
       1  int     NA      Sum of all the elements.
========  ======  ======  ========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int* array - Array to be worked upon.
	 * int length - Length of the passed array.
	 */
	
	int sum_of_all_elements(int *array, int length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int sum_of_all_elements(int *array, int length)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------
asg_a2210 : Array - Check for value in given array.
---------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``is_member()`` that takes a value, list of values, and returns 0 if the value is present in the array, -1 otherwise. 


'''''''
Samples
'''''''
========  =========================  =======================  ========
  Number  Explanation                Input                      Output
========  =========================  =======================  ========
       1  Check for a general case.  [3, [1, 2, 3, 4, 5], 5]         0
       2  Check for a general case.  [8, [1, 2, 3, 4, 5], 5]        -1
========  =========================  =======================  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int is_member(int value, int *array, int length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =======================================  =========
  Number  Type    Name    Explanation                              Remarks
========  ======  ======  =======================================  =========
       1  int     value   value to search.
       1  int     array   the array in which the value to search.
       1  int     length  the length of the passed array.
========  ======  ======  =======================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===============================================  =========
  Number  Type    Name    Explanation                                      Remarks
========  ======  ======  ===============================================  =========
       1  int     NA      0 if the value is present in the array, else -1
========  ======  ======  ===============================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int value - value to search.
	 * int array - the array in which the value to search.
	 * int length - the length of the passed array.
	 */
	
	int is_member(int value, int *array, int length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int is_member(int value, int *array, int length)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------------------------------------
asg_a0920 : Array - Convert a number like 123456 to an array as { 1, 2, 3, 4, 5, 6 }.
-------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``convert_number_to_array()``  which takes input an integer and splits up the digits to store it into an array. Each element of the array has respective digits of the input number. The function should return the resulted array


'''''''
Samples
'''''''
========  =========================  =======  ===============
  Number  Explanation                  Input  Output
========  =========================  =======  ===============
       1  Check for a general case.    12345  [1, 2, 3, 4, 5]
========  =========================  =======  ===============


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``void convert_number_to_array(int input_num, int *array, int length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  =========  =============================================  =========
  Number  Type    Name       Explanation                                    Remarks
========  ======  =========  =============================================  =========
       1  int     input_num  Input number to split into array
       1  int *   array      Array in which the output needs to be copied.
       1  int     length     Length of the array.
========  ======  =========  =============================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ====================  =========
  Number  Type    Name    Explanation           Remarks
========  ======  ======  ====================  =========
       1  void    NA      Nothing is returned.
========  ======  ======  ====================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int input_num - Input number to split into array
	 * int * array - Array in which the output needs to be copied.
	 * int length - Length of the array.
	 */
	
	void convert_number_to_array(int input_num, int *array, int length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void convert_number_to_array(int input_num, int *array, int length)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------------------------------------
asg_a0921 : Array - Convert a number like 123456 to an array as { 6, 5, 4, 3, 2, 1 }.
-------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``convert_number_to_array_reversed()``which saves the digits of an integer into an array. The numbers should be saved in the reversed order.


'''''''
Samples
'''''''
========  =========================  =======  ==================
  Number  Explanation                  Input  Output
========  =========================  =======  ==================
       1  Check for a general case.   123456  [6, 5, 4, 3, 2, 1]
========  =========================  =======  ==================


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``void convert_number_to_array_reversed(int input_num, int *array, int length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  =========  =============================================  =========
  Number  Type    Name       Explanation                                    Remarks
========  ======  =========  =============================================  =========
       1  int     input_num  Input number to split into array
       2  int *   array      Array in which the output needs to be copied.
       3  int     length     Length of the array.
========  ======  =========  =============================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ====================  =========
  Number  Type    Name    Explanation           Remarks
========  ======  ======  ====================  =========
       1  void    NA      Nothing is returned.
========  ======  ======  ====================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int input_num - Input number to split into array
	 * int * array - Array in which the output needs to be copied.
	 * int length - Length of the array.
	 */
	
	void convert_number_to_array_reversed(int input_num, int *array, int length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void convert_number_to_array_reversed(int input_num, int *array, int length)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------------------------
asg_a0651 : Array - Find the product of all the elements stored in the array.
-----------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``product_of_array(int arr)`` which multiplies all the elements of the array and returns the multiplied result value. The function takes an array as input. Return 0 if the array is empty.


'''''''
Samples
'''''''
========  ==================================  ==============  ========
  Number  Explanation                         Input             Output
========  ==================================  ==============  ========
       1  Check for a general case.           [10, 20, 2, 4]      1600
       2  Check when zero as an input number  [10, 20, 0, 4]         0
       3  Check for empty array               []                     0
========  ==================================  ==============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int product_of_array(int *array, int length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ============================  =========
  Number  Type    Name    Explanation                   Remarks
========  ======  ======  ============================  =========
       1  int     arr     Array of integers.
       2  int     arr     Length of the integer array.
========  ======  ======  ============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ====================================================  =========
  Number  Type    Name    Explanation                                           Remarks
========  ======  ======  ====================================================  =========
       1  int     NA      The multiplied value of all the numbers in the array
========  ======  ======  ====================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int arr - Array of integers.
	 * int arr - Length of the integer array.
	 */
	
	int product_of_array(int *array, int length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int product_of_array(int *array, int length)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------------------
asg_a0652 : Array - Find the maximum and minimum element of an array
--------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_min_max(int arr)`` which returns the minimum and maximum element contained in a 1 D array. An integer array is passed as input to the function.  Return 0 if successful. If the array is empty then return -1.


'''''''
Samples
'''''''
========  ==================================  ==================  =========
  Number  Explanation                         Input               Output
========  ==================================  ==================  =========
       1  Check for a general case.           [10, 20, 2, 4]      [2, 20]
       2  Check when zero as an input number  [10, 20, 0, 4]      [0, 20]
       3  Check for empty array               []                  0
       4  Check for negative values           [-20, -10, -5, -1]  [-20, -1]
========  ==================================  ==================  =========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_min_max(int *array, int length, int *result_array, int result_array_length)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ===================  =========================================================================  =========
  Number  Type    Name                 Explanation                                                                Remarks
========  ======  ===================  =========================================================================  =========
       1  int*    array                Single dimensional array of integers.
       2  int     length               Length of the single dimensional array.
       3  int *   result_array         An array of length 2, put minimum in 0th index, and maximum at 1st index.
       4  int *   result_array_length  The length of the result array.
========  ======  ===================  =========================================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==============================================================  =========
  Number  Type    Name    Explanation                                                     Remarks
========  ======  ======  ==============================================================  =========
       1  int     NA      0 if minimum and maximum was found, -1 if the array was empty.
========  ======  ======  ==============================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int* array - Single dimensional array of integers.
	 * int length - Length of the single dimensional array.
	 * int * result_array - An array of length 2, put minimum in 0th index, and maximum at 1st index.
	 * int * result_array_length - The length of the result array.
	 */
	
	int find_min_max(int *array, int length, int *result_array, int result_array_length) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_min_max(int *array, int length, int *result_array, int result_array_length)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------------------------------------------------------------------
asg_a0656 : Array - Fill an array with the multiples of 3, then replace the the numbers which are divisible by 5 by -1.
-----------------------------------------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``fill_array(int n)`` which fills the array of n length with multiples of 3. Then replace the numbers which are divisible by 5. This would leave you with few empty spaces in the array. Fill these empty spaces with -1. Return the finally generated array.


'''''''
Samples
'''''''
========  ==================================  =======  =====================================
  Number  Explanation                         Input    Output
========  ==================================  =======  =====================================
       1  Check for a general case.           [5]      [3, 6, 9, 12, -1]
       2  Check when zero as an input number  [10]     [3, 6, 9, 12, -1, 18, 21, 24, 27, -1]
       3  Check for empty array               [0]      0
========  ==================================  =======  =====================================


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``void fill_array(int n, int *array)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==============================================================================  =========
  Number  Type    Name    Explanation                                                                     Remarks
========  ======  ======  ==============================================================================  =========
       1  int     n       Length of the array
       2  int *   array   The array to be filled. The length of the array will be equal to the n passed.
========  ======  ======  ==============================================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===================================================  =========
  Number  Type    Name    Explanation                                          Remarks
========  ======  ======  ===================================================  =========
       1  int     NA      Newly generated array after additions and removals.
========  ======  ======  ===================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int n - Length of the array
	 * int * array - The array to be filled. The length of the array will be equal to the n passed.
	 */
	
	void fill_array(int n, int *array) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void fill_array(int n, int *array)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------------------
asg_a2207 : Array - Perform sum and multiplication of multiple elements in an array.
------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Define a function ``sum_and_multiply()`` which multiplies the elements in an array as well as adds all the elements in an array and returns the final sum and product. Return 0 if successful. If the array is of length 0 then return -1.


'''''''
Samples
'''''''
========  ====================================================  ===========================  ========
  Number  Explanation                                           Input                          Output
========  ====================================================  ===========================  ========
       1  Sum works correctly.                                  [1, 2, 3, 4]                       10
       2  Sum works correctly for negative numbers.             [1, -1, 2, -2, 4]                   4
       3  Multiplication works correctly.                       [1, 2, 3, 4, 5]                    15
       4  Multiplication works correctly for negative numbers.  [1, -2, 3, 4]                       5
       5  Multiplication works correctly for large numbers.     [1000000, 2000000, 9000000]  12000000
========  ====================================================  ===========================  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int sum_and_multiply(int *array, int length, int *sum, int *product)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  =======  ============================================  =========
  Number  Type    Name     Explanation                                   Remarks
========  ======  =======  ============================================  =========
       1  int *   array    List of integers to be worked upon.
       1  int     length   Length of the array passed.
       1  int *   sum      Pass by reference for returning the sum.
       1  int *   product  Pass by reference for returning the product.
========  ======  =======  ============================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==============================================================================================  =========
  Number  Type    Name    Explanation                                                                                     Remarks
========  ======  ======  ==============================================================================================  =========
       1  int     NA      Return value based on the length of the array. 0 if the length is more that 0, else return -1.
========  ======  ======  ==============================================================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int * array - List of integers to be worked upon.
	 * int length - Length of the array passed.
	 * int * sum - Pass by reference for returning the sum.
	 * int * product - Pass by reference for returning the product.
	 */
	
	int sum_and_multiply(int *array, int length, int *sum, int *product) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int sum_and_multiply(int *array, int length, int *sum, int *product)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------------
asg_a2425 : Array - Count the odd numbers in the even indexes.
--------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_odd_numbers_at_even_places()`` which stores the odd numbers in the array in another array, and also returns the length of the returning array. If the array is of length 0 return -1, else return 0.


'''''''
Samples
'''''''
========  =========================  ===============  ========
  Number  Explanation                Input            Output
========  =========================  ===============  ========
       1  Check for a general case.  [1, 2, 2, 4, 4]  [2, 4]
========  =========================  ===============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_odd_numbers_at_even_places(int *array, int length, int *ret_array, int *ret_array_elements)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ==============  ==================  =============================================================================  =========
  Number  Type            Name                Explanation                                                                    Remarks
========  ==============  ==================  =============================================================================  =========
       1  int *           array               Array to be worked upon.
       2  int             length              Length of the array to be worked upon. This is also the size of the ret_array
       3  int *ret_array  ret_array           Array with the odd numbers of the passed array stored.
       4  int *           ret_array_elements  Number of odd numbers found at even places, pass by reference.
========  ==============  ==================  =============================================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==========================================================  =========
  Number  Type    Name    Explanation                                                 Remarks
========  ======  ======  ==========================================================  =========
       1  int     NA      If the passes array has 0 length return -1, else return 0.
========  ======  ======  ==========================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int * array - Array to be worked upon.
	 * int length - Length of the array to be worked upon. This is also the size of the ret_array
	 * int *ret_array ret_array - Array with the odd numbers of the passed array stored.
	 * int * ret_array_elements - Number of odd numbers found at even places, pass by reference.
	 */
	
	int find_odd_numbers_at_even_places(int *array, int length, int *ret_array, int *ret_array_elements) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_odd_numbers_at_even_places(int *array, int length, int *ret_array, int *ret_array_elements)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------------------------------------
asg_a0664 : Array - Write a program to find all the prime numbers in a range of 1 to N.
---------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``generate_prime_numbers()`` which will generate numbers from 1 to N and put it in an array. If the length of array passed is less than the numbers generated then return -1, else return 0.


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

``int generate_prime_numbers(int n, int *array, int length, int *elements_filled)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ========================================================  =========
  Number  Type    Name    Explanation                                               Remarks
========  ======  ======  ========================================================  =========
       1  int     n       Number till where we have to generate the prime numbers.
       1  int *   array   Array to be filled.
       1  char *  str     Length of the passed array.
       1  char *  str     Elements filled in the array.
========  ======  ======  ========================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =======================================================================================================================  =========
  Number  Type    Name    Explanation                                                                                                              Remarks
========  ======  ======  =======================================================================================================================  =========
       1  int     NA      Return -1 if the number of elements generated is more than the length of the length of the array passed, else return 0.
========  ======  ======  =======================================================================================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int n - Number till where we have to generate the prime numbers.
	 * int * array - Array to be filled.
	 * char * str - Length of the passed array.
	 * char * str - Elements filled in the array.
	 */
	
	int generate_prime_numbers(int n, int *array, int length, int *elements_filled) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int generate_prime_numbers(int n, int *array, int length, int *elements_filled)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------------------
asg_a0277 : Loop - Write a function ``print_pattern_04()`` which prints the pattern.
------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::
    
    HELLOXHELLO
    HELLO HELLO
    HELL   ELLO
    HEL     LLO
    HE       LO
    H         O
    HE       LO
    HEL     LLO
    HELL   ELLO
    HELLO HELLO
    HELLOXHELLO



'''''''
Samples
'''''''
========  =============  =======  ========
  Number  Explanation    Input    Output
========  =============  =======  ========
       1                          #
========  =============  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``void print_pattern_04(void)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ========================================  =========
  Number  Type    Name    Explanation                               Remarks
========  ======  ======  ========================================  =========
       1  void            Nothing will be passed to this function.
========  ======  ======  ========================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==========================================  =========
  Number  Type    Name    Explanation                                 Remarks
========  ======  ======  ==========================================  =========
       1  void    NA      Nothing will be returned in this function.
========  ======  ======  ==========================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * void  - Nothing will be passed to this function.
	 */
	
	void print_pattern_04(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern_04(void)
	}

.. raw:: latex

    \clearpage
