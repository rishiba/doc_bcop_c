

===========
Basics Of C
===========


*********************************
Basics of Functions and Operators
*********************************


---------------------------------
asg_a2300 : Number - Add 5 and 6.
---------------------------------


'''''''''''
Description
'''''''''''

Write a function ``add_5_6()`` to add 5 and 6 and return the output.


'''''''
Samples
'''''''
========  ============================  ========  ========
  Number  Explanation                   Input       Output
========  ============================  ========  ========
       1  Check if the function works.  No Input        11
========  ============================  ========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int add_5_6(void)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================  =========
  Number  Type    Name    Explanation            Remarks
========  ======  ======  =====================  =========
       1  void            Nothing to be passed.
========  ======  ======  =====================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===============  =========
  Number  Type    Name    Explanation      Remarks
========  ======  ======  ===============  =========
       1  int     NA      Sum of 5 and 6.
========  ======  ======  ===============  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * void  - Nothing to be passed.
	 */
	
	int add_5_6(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int add_5_6(void)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------
asg_a2303 : Number - Find the product of 200 and 3.
---------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``find_product_200_and_3()`` to find the product of 200 and 3


'''''''
Samples
'''''''
========  ============================  ========  ========
  Number  Explanation                   Input       Output
========  ============================  ========  ========
       1  Check if the function works.  No Input       600
========  ============================  ========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_product_200_and_3(void)``


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
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     NA      The product of 200 and 3.
========  ======  ======  =========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * void  - Nothing needs to be passed to this function.
	 */
	
	int find_product_200_and_3(void) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_product_200_and_3(void)
	}

.. raw:: latex

    \clearpage


-------------------------------------
asg_a0017 : Number - Find the profit.
-------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``get_profit()`` which when passed the cost price and the profit percentage, returns the profit. Ignore the decimal points.


'''''''
Samples
'''''''
========  =======================================  ==========  ========
  Number  Explanation                              Input         Output
========  =======================================  ==========  ========
       1  Check if function is working correctly.  [1000, 20]       200
========  =======================================  ==========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int get_profit(int costprice, int profit_percent)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================================  =========
  Number  Type    Name    Explanation                            Remarks
========  ======  ======  =====================================  =========
       1  int     cp      The cost price of the product.
       2  int     profit  The profit percentage of the product.
========  ======  ======  =====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     NA      Profit amount calculated.
========  ======  ======  =========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int cp - The cost price of the product.
	 * int profit - The profit percentage of the product.
	 */
	
	int get_profit(int costprice, int profit_percent) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int get_profit(int costprice, int profit_percent)
	}

.. raw:: latex

    \clearpage


-------------------------------------
asg_a2301 : Number - Add two numbers.
-------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``add_two_numbers()`` which takes two numbers as input from the user and prints the sum to the screen.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                  Input      Output
========  ===========================  =======  ========
       1  Check for positive numbers.  [5, 6]         11
       2  Check for negative number.   [5, -6]        -1
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int add_two_numbers(int num1, int num2)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==========================  =========
  Number  Type    Name    Explanation                 Remarks
========  ======  ======  ==========================  =========
       1  int     num1    First number to be added.
       2  int     num2    Second number to be added.
========  ======  ======  ==========================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==============================  =========
  Number  Type    Name    Explanation                     Remarks
========  ======  ======  ==============================  =========
       1  int     NA      Return the sum of two numbers.
========  ======  ======  ==============================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num1 - First number to be added.
	 * int num2 - Second number to be added.
	 */
	
	int add_two_numbers(int num1, int num2) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int add_two_numbers(int num1, int num2)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------------
asg_a0009 : Number - Add 1 to all the digits of a 5 digit number.
-----------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``add_one_to_digits()`` which adds 1 to all the digits of a 5 digit number. The input will never have digit 9.


'''''''
Samples
'''''''
========  =========================  =======  ========
  Number  Explanation                  Input    Output
========  =========================  =======  ========
       1  Check for a general case.    12345     23456
========  =========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int add_one_to_digits(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =============================  =========
  Number  Type    Name    Explanation                    Remarks
========  ======  ======  =============================  =========
       1  int     number  The number to be worked upon.
========  ======  ======  =============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ==========================================  =========
  Number  Type    Name    Explanation                                 Remarks
========  ======  ======  ==========================================  =========
       1  int     NA      The number after adding one to all digits.
========  ======  ======  ==========================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - The number to be worked upon.
	 */
	
	int add_one_to_digits(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int add_one_to_digits(int number)
	}

.. raw:: latex

    \clearpage


--------------------------------------------------------
asg_a0019 : Number - Find the circumference of a circle.
--------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``get_circumference()`` which when passed the radius returns the circumference.


'''''''
Samples
'''''''
========  ==============================================  =======  ========
  Number  Explanation                                       Input    Output
========  ==============================================  =======  ========
       1  Check if function is proper                        20      125.6
       2  Check if function is proper                        20.3    127.48
       3  Check if function is proper for negative input    -20        0
========  ==============================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``double get_circumference(double radius)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================  =========
  Number  Type    Name    Explanation            Remarks
========  ======  ======  =====================  =========
       1  double  radius  radius of the circle.
========  ======  ======  =====================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  double  NA      Return the calculated circumference.
========  ======  ======  ====================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * double radius - radius of the circle.
	 */
	
	double get_circumference(double radius) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // double get_circumference(double radius)
	}

.. raw:: latex

    \clearpage


-------------------------------------------
asg_a0032 : Number - Convert Kms to Meters.
-------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``convert_kms_to_mts()`` which takes as input KMs and returns the converted value in Meters. Your function will not be tested for zero or negative values.


'''''''
Samples
'''''''
========  ==============================  =======  ========
  Number  Explanation                     Input      Output
========  ==============================  =======  ========
       1  Check for basic functionality.  [1000]    1000000
       2  Check for negative numbers.     [-1000]  -1000000
       3  Check for 0.                    0               0
========  ==============================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int convert_kms_to_mts (int kms)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==============================  =========
  Number  Type    Name    Explanation                     Remarks
========  ======  ======  ==============================  =========
       1  int     kms     KMs to be converted to meters.
========  ======  ======  ==============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =========================  =========
  Number  Type    Name    Explanation                Remarks
========  ======  ======  =========================  =========
       1  int     NA      Return the KMs in meters.
========  ======  ======  =========================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int kms - KMs to be converted to meters.
	 */
	
	int convert_kms_to_mts (int kms) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int convert_kms_to_mts (int kms)
	}

.. raw:: latex

    \clearpage


------------------------------------------------
asg_a0034 : Number - Convert KMs to Millimeters.
------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``convert_kms_to_mms()`` which when passed value in KMs returns values in Millimeters. Your function will not be tested for negative values.


'''''''
Samples
'''''''
========  =============================  =======  ========
  Number  Explanation                    Input      Output
========  =============================  =======  ========
       1  Check for basic functionality  [1]       1000000
       2  Check for negative values      [-1]     -1000000
       3  Check for zero                 0               0
========  =============================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int convert_kms_to_mms(int kms)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ==============================  =========
  Number  Type    Name    Explanation                     Remarks
========  ======  ======  ==============================  =========
       1  int     kms     KMs to convert to Millimeters.
========  ======  ======  ==============================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  int     NA      Return KMs converted to milli meters
========  ======  ======  ====================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int kms - KMs to convert to Millimeters.
	 */
	
	int convert_kms_to_mms(int kms) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int convert_kms_to_mms(int kms)
	}

.. raw:: latex

    \clearpage


-----------------------------------------
asg_a0033 : Number - Convert KMs to feet.
-----------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``convert_kms_to_feet()`` which when passed values in KMs returns the Feet.


'''''''
Samples
'''''''
========  =============================  =======  =========
  Number  Explanation                    Input       Output
========  =============================  =======  =========
       1  Check for basic case.          [1]        3280.84
       2  Check for another basic case.  [100]    328084
       3  Check for zero value.          [0]           0
       4  Check for negative number.     [-1]      -3280.84
========  =============================  =======  =========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``float convert_kms_to_feet(int kms)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  =======  ======  =====================================  =========
  Number  Type     Name    Explanation                            Remarks
========  =======  ======  =====================================  =========
       1  integer  kms     Kilometers to be converted into feet.
========  =======  ======  =====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ================================  =========
  Number  Type    Name    Explanation                       Remarks
========  ======  ======  ================================  =========
       1  float   NA      Number of feet in the Kilometer.
========  ======  ======  ================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * integer kms - Kilometers to be converted into feet.
	 */
	
	float convert_kms_to_feet(int kms) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // float convert_kms_to_feet(int kms)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------
asg_a0036 : Number - Convert Fahrenheit to Celsius.
---------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``convert_fahrenheit_to_celsius()`` which when passed value in Fahrenheit returns the converted value in Celsius.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                  Input      Output
========  ===========================  =======  ========
       1  Check if function is proper  [68]        20
       2  Check if function is proper  [-68]      -55.56
       3  Check if function is proper  [0]        -17.78
       4  Check if function is proper  [32]         0
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``double convert_fahrenheit_to_celsius(int fht_temp)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ========  ==================================================  =========
  Number  Type    Name      Explanation                                         Remarks
========  ======  ========  ==================================================  =========
       1  int     fht_temp  Fahrenheit temperature to be converted to Celsius.
========  ======  ========  ==================================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =======================  =========
  Number  Type    Name    Explanation              Remarks
========  ======  ======  =======================  =========
       1  double  NA      Temperature in Celsius.
========  ======  ======  =======================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int fht_temp - Fahrenheit temperature to be converted to Celsius.
	 */
	
	double convert_fahrenheit_to_celsius(int fht_temp) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // double convert_fahrenheit_to_celsius(int fht_temp)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------
asg_a0011 : Number - Sum of the digits of a 5 digit number.
-----------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``sum_of_5_digits()`` which takes an integer and returns the sum of the numbers. Your function will not be tested for the numbers which is less than zero, zero, or less than 5 digits.


'''''''
Samples
'''''''
========  =========================================  =======  ========
  Number  Explanation                                  Input    Output
========  =========================================  =======  ========
       1  Check if function is proper for 5 digits.    12345        15
========  =========================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int sum_of_5_digits(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ====================================  =========
  Number  Type    Name    Explanation                           Remarks
========  ======  ======  ====================================  =========
       1  int     number  Number whose digits are to be added.
========  ======  ======  ====================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ======================  =========
  Number  Type    Name    Explanation             Remarks
========  ======  ======  ======================  =========
       1  int     NA      Sum of all the digits.
========  ======  ======  ======================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number whose digits are to be added.
	 */
	
	int sum_of_5_digits(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int sum_of_5_digits(int number)
	}

.. raw:: latex

    \clearpage


------------------------------------------------------------
asg_a0040 : Number - Average of digits for a 5 digit number.
------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function to ``find_five_digits_average()`` which when passed a 5 digit number returns the average of the digits. Ignore the decimals.


'''''''
Samples
'''''''
========  ========================================  ========  ========
  Number  Explanation                               Input       Output
========  ========================================  ========  ========
       1  Check if function is proper               [53161]          3
       2  Check if function is proper for negative  [-53161]         3
========  ========================================  ========  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int find_five_digits_average(int num)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =================================  =========
  Number  Type    Name    Explanation                        Remarks
========  ======  ======  =================================  =========
       1  int     num     5 digit number to be worked upon.
========  ======  ======  =================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =====================================  =========
  Number  Type    Name    Explanation                            Remarks
========  ======  ======  =====================================  =========
       1  int     NA      Average of digits of a 5 digit number
========  ======  ======  =====================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int num - 5 digit number to be worked upon.
	 */
	
	int find_five_digits_average(int num) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int find_five_digits_average(int num)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------
asg_a0045 : Number - Find the volume of a cube.
-----------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``cube_volume()`` which when passed the side of a cube, returns the volume of the cube.


'''''''
Samples
'''''''
========  =======================  =======  ========
  Number  Explanation                Input    Output
========  =======================  =======  ========
       1  Check for basic values.        5       125
========  =======================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int cube_volume(int side)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =================  =========
  Number  Type    Name    Explanation        Remarks
========  ======  ======  =================  =========
       1  int     side    Side of the cube.
========  ======  ======  =================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===================  =========
  Number  Type    Name    Explanation          Remarks
========  ======  ======  ===================  =========
       1  int     NA      Volume of the cube.
========  ======  ======  ===================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int side - Side of the cube.
	 */
	
	int cube_volume(int side) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int cube_volume(int side)
	}

.. raw:: latex

    \clearpage


-------------------------------------------
asg_a0031 : Number - Find the gross salary.
-------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``calculate_gross_salary()`` which when passed the Basic salary, Dearness Allowance (in percentage of Basic) and House Rent Allowance in rupees, calculates and returns the gross salary, which is the sum of all three.


'''''''
Samples
'''''''
========  ===========================  =================  ========
  Number  Explanation                  Input                Output
========  ===========================  =================  ========
       1  Check if function is proper  [20000, 10, 5000]     27000
========  ===========================  =================  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int calculate_gross_salary(int basic_salary, int dearness_allowance, int house_rent)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ==================  =========================================  =========
  Number  Type    Name                Explanation                                Remarks
========  ======  ==================  =========================================  =========
       1  int     basic_salary        Basic Salary in Rupees
       2  int     dearness_allowance  Dearness Allowance in percentage of Basic
       3  int     house_rent          House Rent Allowance in Rupees
========  ======  ==================  =========================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =======================  =========
  Number  Type    Name    Explanation              Remarks
========  ======  ======  =======================  =========
       1  int     NA      Calculated Gross Salary
========  ======  ======  =======================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int basic_salary - Basic Salary in Rupees
	 * int dearness_allowance - Dearness Allowance in percentage of Basic
	 * int house_rent - House Rent Allowance in Rupees
	 */
	
	int calculate_gross_salary(int basic_salary, int dearness_allowance, int house_rent) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int calculate_gross_salary(int basic_salary, int dearness_allowance, int house_rent)
	}

.. raw:: latex

    \clearpage


---------------------------------------------------------------------------
asg_a0006 : Number - Calculate the amount after adding the simple interest.
---------------------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``get_si_amount()`` which will take principle, rate of interest, and time in years and return the amount. Ignore decimal values.


'''''''
Samples
'''''''
========  ======================================================  =============  ========
  Number  Explanation                                             Input            Output
========  ======================================================  =============  ========
       1  See if the function works correctly for simple inputs.  [10000, 5, 2]     11000
       2  See if it works for 0% interest                         [1000, 0, 2]       1000
       3  See if it works for 0 Months                            [1000, 5, 0]       1000
========  ======================================================  =============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int get_si_amount (int principle, int rate, int years)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  =========  ===========================================  =========
  Number  Type    Name       Explanation                                  Remarks
========  ======  =========  ===========================================  =========
       1  int     principle  Principle amount to be used for calculation
       2  int     rate       Rate percentage to be used for calculation
       3  int     years      Number of years to be used for calculation
========  ======  =========  ===========================================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =================  =========
  Number  Type    Name    Explanation        Remarks
========  ======  ======  =================  =========
       1  int     NA      Calculated amount
========  ======  ======  =================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int principle - Principle amount to be used for calculation
	 * int rate - Rate percentage to be used for calculation
	 * int years - Number of years to be used for calculation
	 */
	
	int get_si_amount (int principle, int rate, int years) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int get_si_amount (int principle, int rate, int years)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------
asg_a0938 : Number - Make number from 5 digits.
-----------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``make_number_from_5_digits()`` which will be passed 5 integers. The function needs to make a number out of them in the order of passed arguments. For example the numbers passed will be 1, 2, 3, 4, 5 and the output will be 12345.


'''''''
Samples
'''''''
========  ==========================================  ===============  ========
  Number  Explanation                                 Input              Output
========  ==========================================  ===============  ========
       1  Five digits to be used for making numbers.  [1, 2, 3, 4, 5]     12345
========  ==========================================  ===============  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int make_number_from_5_digits(int a, int b, int c, int d, int e)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =============  =========
  Number  Type    Name    Explanation    Remarks
========  ======  ======  =============  =========
       1  int     a       First digit
       2  int     b       Second digit
       3  int     c       Third digit
       4  int     d       Fourth digit
       5  int     e       Fifth digit
========  ======  ======  =============  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===================================  =========
  Number  Type    Name    Explanation                          Remarks
========  ======  ======  ===================================  =========
       1  int     NA      Number made from the passed values.
========  ======  ======  ===================================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int a - First digit
	 * int b - Second digit
	 * int c - Third digit
	 * int d - Fourth digit
	 * int e - Fifth digit
	 */
	
	int make_number_from_5_digits(int a, int b, int c, int d, int e) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int make_number_from_5_digits(int a, int b, int c, int d, int e)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------------------
asg_a0012 : Number - Product of digits of a 5 digit number.
-----------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``product_of_5_digits()`` which returns the products of the digits passed to the function. Your function will not be checked for negative numbers or numbers with zeros. Your function will not be checked for numbers less than 5 digits.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                    Input    Output
========  ===========================  =======  ========
       1  Check if function is proper    12345       120
========  ===========================  =======  ========


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


-------------------------------------------------------------
asg_a0042 : Number - Rotate by 3 places for a 5 digit number.
-------------------------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``rotate_left_by_3_5_digits()`` which takes input a number and rotates the number to the left by 3 digits. Your function will not be checked against a negative number, a number with zeros. You can solve this in one line of code.


'''''''
Samples
'''''''
========  ===========================  =======  ========
  Number  Explanation                    Input    Output
========  ===========================  =======  ========
       1  Check if function is proper    12345     45123
========  ===========================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int rotate_left_by_3_5_digits(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  =====================  =========
  Number  Type    Name    Explanation            Remarks
========  ======  ======  =====================  =========
       1  int     number  Number to be rotated.
========  ======  ======  =====================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  ===============  =========
  Number  Type    Name    Explanation      Remarks
========  ======  ======  ===============  =========
       1  int     NA      Rotated number.
========  ======  ======  ===============  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number to be rotated.
	 */
	
	int rotate_left_by_3_5_digits(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int rotate_left_by_3_5_digits(int number)
	}

.. raw:: latex

    \clearpage


-----------------------------------------------
asg_a0010 : Number - Reverse a 5 digit integer.
-----------------------------------------------


'''''''''''
Description
'''''''''''

Write a function ``reverse_5_digit_int()`` which takes a 5 digit integer and returns the reverse of it. Your function will not be tested for number less than zero and numbers ending with zeros.


'''''''
Samples
'''''''
========  ===========================================================  =======  ========
  Number  Explanation                                                    Input    Output
========  ===========================================================  =======  ========
       1  Check if function is properly working for a random integer.    12345     54321
========  ===========================================================  =======  ========


''''''''
Function
''''''''


^^^^^^^^^^^^^^^^^^
Function Signature
^^^^^^^^^^^^^^^^^^

``int reverse_5_digit_int(int number)``


^^^^^^^^^^^^^^^^^^
Function Arguments
^^^^^^^^^^^^^^^^^^
========  ======  ======  ======================  =========
  Number  Type    Name    Explanation             Remarks
========  ======  ======  ======================  =========
       1  int     number  Number to be reversed.
========  ======  ======  ======================  =========


^^^^^^^^^^^^
Return Value
^^^^^^^^^^^^
========  ======  ======  =============================  =========
  Number  Type    Name    Explanation                    Remarks
========  ======  ======  =============================  =========
       1  int     NA      Returned the reversed number.
========  ======  ======  =============================  =========


''''''''''''''''''''
Function Placeholder
''''''''''''''''''''

::

	/*
	 * int number - Number to be reversed.
	 */
	
	int reverse_5_digit_int(int number) {
	
	    // Write the function body here.
	
	}
	
	int main() {
	
	    // Call the function here with right parameters.
	    // int reverse_5_digit_int(int number)
	}

.. raw:: latex

    \clearpage
