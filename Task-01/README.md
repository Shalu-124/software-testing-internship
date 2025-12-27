Task-01: Test Cases for Simple Calculator Applications
Addition – Test Cases
Test Case Id:
TC_001
Test Description:

Verify addition of two positive numbers
Precondition:

Calculator application is opened

Test Steps:

Enter 2
Click +
Enter 3
Click =
Expected Result: Result should be 5

Test Case Id:
TC_002
Test Description:

 Verify addition of two negative numbers
Precondition:

Calculator application is opened

Test Steps:

Enter -4
Click +
Enter -6
Click =
Expected Result: Result should be -10

Test Case Id:
TC_003
Test Description:

Verify addition of decimal numbers

Precondition:

Calculator application is opened

Test Steps:

Enter 2.5
Click +
Enter 1.5
Click =
Expected Result: Result should be 4.0

Subtraction – Test Cases
Test Case Id:
TC_004
Test Description:

  Verify subtraction of two positive numbers
Precondition:

Calculator application is opened

Test Steps:

Enter 1
Click -
Enter 4
Click =
Expected Result: Result should be 6.

Test Case Id:
TC_005
Test Description:

Verify subtraction resulting in negative value

Precondition:

Calculator application is opened

Test Steps:

Enter 3
Click -
Enter 8
Click =
Expected Result: Result should be -5

Multiplication – Test Cases
Test Case Id:
TC_006
Test Description:

 Verify multiplication of two numbers
Precondition:

Calculator application is opened

Test Steps:

Enter 6
Click *
Enter 7
Click =
Expected Result: Result should be 42

Test Case Id:

TC_007

Test Description:

   Verify multiplication with zero
Precondition:

Calculator application is opened

Test Steps:

Enter 9
Click *
Enter 0
Click =
Expected Result: Result should be 0

Test Case Id:
TC_008
Test Description:

Verify multiplication of decimal numbers
Precondition:

Calculator application is opened

Test Steps:

Enter 2.5
Click *
Enter 4
Click =
Expected Result: Result should be 10

Division – Test Cases

Test Case Id:
TC_009
Test Description:

   Verify division of two positive numbers
Precondition:

Calculator application is opened

Test Steps:

1. Enter 20
2. Click /
3. Enter 4
4. Click =

Expected Result: Result should be 5

Test Case Id:
TC_010
Test Description:

  Verify division resulting in decimal value
Precondition:

Calculator application is opened

Test Steps:

Enter 7
Click /
Enter 2
Click =
Expected Result: Result should be 3.5

Test Case Id:
TC_011
Test Description:

 Verify division by zero  
Precondition:

Calculator application is opened

Test Steps:

Enter 8
Click /
Enter 0
Click =
Expected Result: Error message should be displayed (e.g., “Cannot divide by zero”)

BODMAS – Test Case
Test Case Id:
TC_012
Test Description:

   Verify calculator follows BODMAS rule
Precondition:

Calculator application is opened

Test Steps:

Enter 2 + 3 * 4
Click =
Expected Result: Result should be 14

Invalid Input – Test Cases
Test Case ID:
TC_013
Test Description:

  Verify behavior for non-numeric input
Precondition:

Calculator application is opened

Test Steps:

Enter a
Click +
Enter 5
Click =
Expected Result: Error message should be displayed

Test Case Id:
TC_014
Test Description:

Verify behavior for special characters

Precondition:

Calculator application is opened

Test Steps:

Enter @
Click +
Enter #
Click =
Expected Result: Error message should be displayed

Test Case Id:

TC_015

Test Description:

Verify behavior when no input is provided

Precondition:

Calculator application is opened

Test Steps:

Click = without entering any value
Expected Result: No result or validation message should be shown
