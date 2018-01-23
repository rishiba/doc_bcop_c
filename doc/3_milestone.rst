

==========
Loops in C
==========


*****
Loops
*****


---------------------------------------------------------------------------------------------
asg_a0666 : Loop - Write a function ``find_sum_till_n()`` which calculates sum till N from 1.
---------------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_sum_till_n()`` which takes input an integer and finds sum till that number.


'''''''
Samples
'''''''
========  =========================  =======  ========
  Number  Explanation                  Input    Output
========  =========================  =======  ========
       1  Check for a general case.        4        10
========  =========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_sum_till_n(int n)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ===========================================  =========
  Number  Type    Name    Explanation                                  Remarks
========  ======  ======  ===========================================  =========
       1  int     n       Numbers till where we need to find the sum.
========  ======  ======  ===========================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===================  =========
  Number  Type    Name    Explanation          Remarks
========  ======  ======  ===================  =========
       1  int     NA      Sum of the numbers.
========  ======  ======  ===================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int n - Numbers till where we need to find the sum.
	 */
	
	int find_sum_till_n(int n) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_sum_till_n(int n)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------------------
asg_a0667 : Loop - Find the Nth element in a geometric progression.
-------------------------------------------------------------------


'''''''''''
Description
'''''''''''




'''''''
Samples
'''''''
========  =========================  =========  ========
  Number  Explanation                Input        Output
========  =========================  =========  ========
       1  Check for a general case.  [2, 2, 3]        16
========  =========================  =========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_nth_element_in_gp(int a, int r, int n)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =================  =========
  Number  Type    Name    Explanation        Remarks
========  ======  ======  =================  =========
       1  int     a       The first term.
       2  int     r       The scale factor.
       3  int     n       The term.
========  ======  ======  =================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =======================  =========
  Number  Type    Name    Explanation              Remarks
========  ======  ======  =======================  =========
       1  int     NA      Return the Nth element.
========  ======  ======  =======================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int a - The first term.
	 * int r - The scale factor.
	 * int n - The term.
	 */
	
	int find_nth_element_in_gp(int a, int r, int n) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_nth_element_in_gp(int a, int r, int n)
	}

.. raw:: latex

    \clearpage


----------------------------------------------------------------------------
asg_a0823 : Loop - Write a program for calculating the factorial of a number
----------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``calculate_factorial()`` which calculates the factorial of a passed number.


'''''''
Samples
'''''''
========  ========================  =======  ========
  Number  Explanation                 Input    Output
========  ========================  =======  ========
       1  Check for a simple case.        3         6
       2  Check for corner case 1.        1         1
       3  Check for corner case 0.        0         1
========  ========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int calculate_factorial(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  int     number  Number whose factorial has to found.
========  ======  ======  ====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =====================================  =========
  Number  Type    Name    Explanation                            Remarks
========  ======  ======  =====================================  =========
       1  int     NA      The calculated factorial of a number.
========  ======  ======  =====================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number whose factorial has to found.
	 */
	
	int calculate_factorial(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int calculate_factorial(int number)
	}

.. raw:: latex

    \clearpage


----------------------------------------------------------
asg_a0824 : Loop - Write a function to calculate pow(x,n)?
----------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_pow(x,n)`` which takes a number and the power to be calculated and returns the result of x to the power n


'''''''
Samples
'''''''
========  ==============================================  =======  ========
  Number  Explanation                                     Input      Output
========  ==============================================  =======  ========
       1  Check if function is proper                     [2, 2]      4
       2  Check if function is proper                     [5, 3]    125
       3  Check if function is proper for negative power  [8, -1]     0.125
========  ==============================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_pow(int x, int n)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =================================================  =========
  Number  Type    Name    Explanation                                        Remarks
========  ======  ======  =================================================  =========
       1  int     x       Number for which the power needs to be calculated
       2  int     n       The power for the number
========  ======  ======  =================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==============================================  =========
  Number  Type    Name    Explanation                                     Remarks
========  ======  ======  ==============================================  =========
       1  int     NA      Calculated result of input raised to the power
========  ======  ======  ==============================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int x - Number for which the power needs to be calculated
	 * int n - The power for the number
	 */
	
	int find_pow(int x, int n) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_pow(int x, int n)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------------------------------
asg_a0274 : Loop - Write a function ``print_pattern_01()`` which prints pattern.
--------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

    ********
    ********
    ********
    ********
    ********



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

``void print_pattern_01(void)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ============================================  =========
  Number  Type    Name    Explanation                                   Remarks
========  ======  ======  ============================================  =========
       1  void            Nothing needs to be passed to this function.
========  ======  ======  ============================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =============================================  =========
  Number  Type    Name    Explanation                                    Remarks
========  ======  ======  =============================================  =========
       1  void    NA      The output needs to be printed on the screen.
========  ======  ======  =============================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * void  - Nothing needs to be passed to this function.
	 */
	
	void print_pattern_01(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern_01(void)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------------------
asg_a0275 : Loop - Write a function ``print_pattern_02()`` which prints the pattern.
------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

    *****
    ****
    ***
    **
    *



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

``void print_pattern_02(void)``


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
	
	void print_pattern_02(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern_02(void)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------------------
asg_a0276 : Loop - Write a function ``print_pattern_03()`` which prints the pattern.
------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


:: 

    *
    **
    ***
    ****
    *****



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

``void print_pattern_03(void)``


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
	
	void print_pattern_03(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern_03(void)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------------------
asg_a0278 : Loop - Write a function ``print_pattern_05()`` which prints the pattern.
------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

    ####*
    ###**
    ##***
    #****
    *****



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

``void print_pattern_05(void)``


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
	
	void print_pattern_05(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern_05(void)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------------------------------
asg_a0279 : Loop - Write a function ``print_pattern_05()`` which prints the pattern.
------------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

        *
       **
      ***
     ****
    *****



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

``void print_pattern_05(void)``


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
	
	void print_pattern_05(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern_05(void)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------------------------------
asg_a0280 : Loop - Write a function ``print_pattern()`` which prints the pattern.
---------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

       ***********
       ***** *****
       ****   ****
       ***     ***
       **       **
       *         *
       **       **
       ***     ***
       ****   ****
       ***** *****
       ***********



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

``void print_pattern(void)``


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
	
	void print_pattern(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern(void)
	}

.. raw:: latex

    \clearpage


-------------------------------------------------------------------------------
asg_a0281 : Loop - Write a function ``print_pattern()`` which prints a pattern.
-------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

         *
        ***
       *****
      *******
     *********
      *******
       *****
        ***
         *



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

``void print_pattern(void)``


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
	
	void print_pattern(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern(void)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------------------------------
asg_a0283 : Loop - Write a function ``print_pattern()`` which prints the pattern.
---------------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

    *********
     *******
      *****
       ***
        *
       ***
      *****
     *******
    *********



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

``void print_pattern(void)``


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
	
	void print_pattern(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern(void)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------------------------
asg_a0284 : Loop - Write a function ``print_pattern()`` to print the pattern.
-----------------------------------------------------------------------------


'''''''''''
Description
'''''''''''


::

            *********
           *********
          *********
         *********
        *********
       *********
      *********



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

``void print_pattern(void)``


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
	
	void print_pattern(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern(void)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------
asg_a2246 : Loop - Sum of even terms in Fibonacci series
--------------------------------------------------------


'''''''''''
Description
'''''''''''

Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, the first 10 terms will be: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89. Write a function which returns the sum of the even numbers in the Fibonacci series for N terms. The function name should be ``find_sum_of_even_numbers_fibonacci()``.


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

``int find_sum_of_even_numbers_fibonacci(int n)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==================================================================  =========
  Number  Type    Name    Explanation                                                         Remarks
========  ======  ======  ==================================================================  =========
       1  int     int     The highest number till which we have to find the Fibonacci terms.
========  ======  ======  ==================================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =================  =========
  Number  Type    Name    Explanation        Remarks
========  ======  ======  =================  =========
       1  int     NA      The result value.
========  ======  ======  =================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int int - The highest number till which we have to find the Fibonacci terms.
	 */
	
	int find_sum_of_even_numbers_fibonacci(int n) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_sum_of_even_numbers_fibonacci(int n)
	}

.. raw:: latex

    \clearpage


-----------------------------------
asg_a2247 : Loop - nth prime number
-----------------------------------


'''''''''''
Description
'''''''''''

By listing the first six prime numbers: 2, 3, 5, 7, 11, and 13, we can see that the 6th prime is 13. Write a function ``find_nth_prime()``.


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

``int find_nth_prime(int n)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================================  =========
  Number  Type    Name    Explanation                            Remarks
========  ======  ======  =====================================  =========
       1  int     n       The nth prime number to be found out.
========  ======  ======  =====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==================================  =========
  Number  Type    Name    Explanation                         Remarks
========  ======  ======  ==================================  =========
       1  int     NA      The value of the nth prime number.
========  ======  ======  ==================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int n - The nth prime number to be found out.
	 */
	
	int find_nth_prime(int n) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_nth_prime(int n)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------------
asg_a0870 : Loop - generate the next prime after a given number
---------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_next_prime(int prime_number)`` which takes input a prime number and returns the next prime number after that input number.


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

``int find_next_prime(int prime_number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ============  ==================  =========
  Number  Type    Name          Explanation         Remarks
========  ======  ============  ==================  =========
       1  int     prime_number  Input prime number
========  ======  ============  ==================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==================================================  =========
  Number  Type    Name    Explanation                                         Remarks
========  ======  ======  ==================================================  =========
       1  int     NA      The next prime number after the input prime number
========  ======  ======  ==================================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int prime_number - Input prime number
	 */
	
	int find_next_prime(int prime_number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_next_prime(int prime_number)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------------------
asg_a0827 : Loop - Write a program to generate Nth Fibonacci number.
--------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``gen_fibonacci()`` which generates the Nth Fibonacci number.


'''''''
Samples
'''''''
========  =============  =======  ========
  Number  Explanation      Input    Output
========  =============  =======  ========
       1                       5         3
========  =============  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int gen_fibonacci(int n)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================================  =========
  Number  Type    Name    Explanation                            Remarks
========  ======  ======  =====================================  =========
       1  int     n       The Fibonacci number to be generated.
========  ======  ======  =====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     NA      The Nth Fibonacci number.
========  ======  ======  =========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int n - The Fibonacci number to be generated.
	 */
	
	int gen_fibonacci(int n) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int gen_fibonacci(int n)
	}

.. raw:: latex

    \clearpage


-----------------------------------------
asg_a0285 : Loop - Program to print a Hut
-----------------------------------------


'''''''''''
Description
'''''''''''


::

            *********
           *********x*
          *********xxx*
         *********xxxxx*
        *********xxxxxxx*
       *********xxxxx xxx*
     ********* xxxxx   xxx*
      ########|xxxxxx xxxx|  
      ########|xxxxxxxxxxx| 
      ###  ###|xxxxxxxxxxx|  
      ###  ###|xxxxxxxxxxx|  
      ###  ###|xxxxxxxxxxx|  
      ---------------------



'''''''
Samples
'''''''
========  =====================================  ==========  ==========
  Number  Explanation                            Input       Output
========  =====================================  ==========  ==========
       1  Check for a general case.              HelloWorld  HeLlOwOrLd
       2  Check for all "lowercase" characters.  helloworld  HeLlOwOrLd
       3  Check for all "UPPERCASE" characters.  HELLOWORLD  HeLlOwOrLd
========  =====================================  ==========  ==========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``void print_pattern(void)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ============================================  =========
  Number  Type    Name    Explanation                                   Remarks
========  ======  ======  ============================================  =========
       1  void            Nothing needs to be passed to this function.
========  ======  ======  ============================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =============================================  =========
  Number  Type    Name    Explanation                                    Remarks
========  ======  ======  =============================================  =========
       1  void    NA      The output needs to be printed on the screen.
========  ======  ======  =============================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * void  - Nothing needs to be passed to this function.
	 */
	
	void print_pattern(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // void print_pattern(void)
	}

.. raw:: latex

    \clearpage
