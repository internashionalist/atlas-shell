0. Write a Bash script that displays Best School 10 times.
You must use the for loop (while and until are forbidden)

1. Write a Bash script that displays Best School 10 times.
You must use the while loop (for and until are forbidden)

2. Write a Bash script that displays Best School 10 times.
You must use the until loop (for and while are forbidden)

3. Write a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line.
You must use the while loop (for and until are forbidden)
You must use the if statement

4. Write a Bash script that loops from 1 to 10 and:
displays bad luck for the 4th loop iteration
displays good luck for the 8th loop iteration
displays Best School for the other iterations
You must use the while loop (for and until are forbidden)
You must use the if, elif and else statements

5. Write a Bash script that displays numbers from 1 to 20 and:
displays 4 and then bad luck from China for the 4th loop iteration
displays 9 and then bad luck from Japan for the 9th loop iteration
displays 17 and then bad luck from Italy for the 17th loop iteration
You must use the while loop (for and until are forbidden)
You must use the case statement

6. Write a Bash script that displays the time for 12 hours and 59 minutes:
display hours from 0 to 12
display minutes from 1 to 59
You must use the while loop (for and until are forbidden)
Note that in this example, we only display the first 70 lines using the head command.

7. Write a Bash script that displays:
The content of the current directory
In a list format
Where only the part of the name after the first dash is displayed (refer to the example)
You must use the for loop (while and until are forbidden)
Do not display hidden files

8. Write a Bash script that gives you information about the school file.
You must use if and, else (case is forbidden)
Your Bash script should check if the file exists and print:
if the file exists: school file exists
if the file does not exist: school file does not exist
If the file exists, print:
if the file is empty: school file is empty
if the file is not empty: school file is not empty
if the file is a regular file: school is a regular file
if the file is not a regular file: (nothing)

9. Write a Bash script that displays numbers from 1 to 100.
Displays FizzBuzz when the number is a multiple of 3 and 5
Displays Fizz when the number is multiple of 3
Displays Buzz when the number is a multiple of 5
Otherwise, displays the number
In a list format

10. Write a Bash script that displays the content of the file /etc/passwd.
Your script should only display:
username
user id
Home directory path for the user
You must use the while loop (for and until are forbidden)

11. Write a Bash script that displays the content of the file /etc/passwd, using the while loop + IFS.
Format: The user USERNAME is part of the GROUP_ID gang, lives in HOME_DIRECTORY and rides COMMAND/SHELL. USER ID's place is protected by the passcode PASSWORD, more info about the user here: USER ID INFO
You must use the while loop (for and until are forbidden)

12. Write a Bash script that displays the visitor IP along with the HTTP status code from the Apache log file.
Format: IP HTTP_CODE
in a list format
See example
You must use awk
You are not allowed to use while, for, until and cut
Download and commit the apache-access.log file along with your answers files

13. Using what you did in the previous exercise, write a Bash script that groups visitors by IP and HTTP status code, and displays this data.
The exact format must be:
OCCURENCE_NUMBER IP HTTP_CODE
In list format
Ordered from the greatest to the lowest number of occurrences
See example
You must use awk
You are not allowed to use while, for, until and cut
