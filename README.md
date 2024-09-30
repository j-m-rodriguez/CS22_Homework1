# CS22_Homework1
Follow these instructions exactly as they are written:

• Open a project in PyCharm names CS22Wk1HW


• Create a Python file in this project named CS22Wk1HW.py.

• Copy and paste the header from the CS22CommentHeader.docx file in the Files area of Canvas and complete the lines for your name, the assignment, and the due date.

• Create a function named main and call it at the end of the program.

• For Program #1, do the following:

o In main, Open a file named numbers.txt for writing. The file object (aka, file proxy) should be named nums (or something similar).

o Use a for loop and the randint method to write 10 numbers to the numbers.txt file that are between 1 and 1000. Each number must be converted a string by using the str function and have a ‘\n’ added to it.

o Close the numbers.txt file.

o Open the numbers.txt file again, but for reading this time.

o Create a function called evensodds that has a file object as a parameter. This function must use a while loop to read each number in the file and determine if it is even or odd. If the number is even, add 1 to a variable to keep track of the number of even numbers. If the number is odd, add 1 to a variable to keep track of odd numbers. When the while loop is finished, the function should return a string saying how many even numbers and odd numbers are in the file. You do not need to include the name of the file in this string.

o When reading numbers from the file in the evensodds function, you will need to use the rstrip method to remove the ‘\n’ from each number and then convert it to an integer using the int function before checking to see if the number is even or odd.

o Call the evensodds function from main and use the print function to display the sentence that is returned.

o Close the numbers.txt file.

• For Program #2, do the following:

o Download the steps.txt file from the Text Files folder in the Files area of Canvas and place it in the same folder as the CS22Wk1HW.py file.

o In main, open the steps.txt file for reading.

o Create a function named get_steps that has three parameters: a string for the name of the month, an integer for the number of days in the month, and a file object. This function must use a for loop to read the number of steps for each day of the month and get the total number of steps for the month. When the for loop is finished, calculate the average number of steps in the month using the integer division operator (//) and then use the print function to display the month and the average number of steps in a sentence.

o Call the get_steps function 12 times from main. Assume February has 28 days.

o Close the steps.txt file.
