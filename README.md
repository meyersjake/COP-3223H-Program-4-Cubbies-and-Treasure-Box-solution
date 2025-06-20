# COP-3223H-Program-4-Cubbies-and-Treasure-Box-solution

Download Here: [COP 3223H Program #4: Cubbies and Treasure Box! solution](https://jarviscodinghub.com/assignment/program-4-cubbies-and-treasure-box-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem A: Cubbies (cubbies.c)
Arup’s daughter Anya just started kindergarten. In her class, each student has a cubbie to put their
personal belongings. Surprisingly, even in this day and age of modern graphics, Anya likes good
ol’ fashion Ascii art!!! Write a program for her that draws a rectangular grid of cubbies based on
some input specifications.
The cubbies will be arranged in a rectangle, with some number or rows and columns, which the
user will enter. In addition, each cubbie will have dimensions h by w characters. The outline of
each cubbie will be drawn with the ‘*’ character and the space inside each cubbie will be
represented by a space (‘ ‘). For example, a 4 x 3 arrangement of cubbies where each cubbie has
dimensions 5 x 7 should be drawn as follows:
**********************
* * * *
* * * *
* * * *
* * * *
**********************
* * * *
* * * *
* * * *
* * * *
**********************
* * * *
* * * *
* * * *
* * * *
**********************
* * * *
* * * *
* * * *
* * * *
**********************
Notice that this design has a total of 4 x 5 + 1 = 21 rows and 3 x 7 + 1 = 22 columns, and that the
size of each cubbie, in terms of space characters drawn is actually 4 x 6. If the rows are labeled
starting at row 0, rows 0, 5, 10, 15 and 20 are the ones that are filled with stars. Similarly, if the
columns are labeled starting at column 0, columns 0, 7, 14 and 21 are the ones that are filled with
stars.
Input Specification
The number of rows and columns specifying the rectangular shape of the cubbies will both be in
between 1 and 10, inclusive. The height and width of each cubbie in characters will both be in
between 2 and 10, inclusive.
Output Specification
Print the design described above as specified. Print one newline character after the end of each
row. Thus, your program should print a total of rows x height + 1 number of newline characters in
total, (along with the other characters…)
Sample Program Run
Please enter the number of rows and columns for the cubbies.
4 3
Please enter the number of rows and columns for the cubbies.
5 7
**********************
* * * *
* * * *
* * * *
* * * *
**********************
* * * *
* * * *
* * * *
* * * *
**********************
* * * *
* * * *
* * * *
* * * *
**********************
* * * *
* * * *
* * * *
* * * *
**********************
Problem B: Treasure Box (treasurebox.py)
In order to encourage good behavior, Anya’s class uses positive reinforcement. If students behave
well, they can get a prize from the treasure box. There are two ways in which a student can earn a
prize from treasure box. Each day of the week, a student’s overall behavior is marked as either
“green” (good), “yellow” (ok) or “red” (bad). If a student gets good behavior for all five days in
the week, she earns one prize from the treasure box. In addition, students can win a sticker if they
do something that is very good. Students can earn at most three stickers in a single day. Once a
student earns 10 stickers, those 10 stickers get turned in for a single treasure box prize!
Write a program to simulate this process. Your program will first ask the user how many days of
school to simulate. For each day, the program will ask the user two questions:
1. What was your overall behavior on day X?
2. How many stickers did you earn on day X?
where X is the day number, starting at 1.
The user will respond with either 0 (green), 1 (yellow), or 2(red) for the first question, and with an
integer in between 0 and 3, inclusive, for the second question.
After asking both questions, if the student earns at least one prize from the treasure box, your
program should print out a message indicating the number of items won from treasure box on that
day.
Note: Stickers roll over. So, for example, if after day 3 you have 9 stickers and you earn 3 stickers
on day 4, you get 1 treasure box item on day 4 AND you keep two stickers at the end of the day
that you can to on day 5.
Input Specification
The first number inputted by the user, the number of days of the simulation will be a positive
integer in between 4 and 50. The rest of the integers entered by the user will be in the ranges
specified previously, in between 0 and 2, inclusive for the daily behavior, and in between 0 and 3,
inclusive for the number of stickers earned for a day.
Output Specification
For each day on which at least one treasure box prize is earned, output a statement of the following
format:
At the conclusion of day X, you received Y treasure box item(s).
where X is the day number, with the first day labeled as 1, and Y is the number of treasure box
items earned on that day.
At the very end of the program, print a single line stating the total number of treasure box items
earned using the following format:
In total, you received Y treasure box item(s).
where Y is the total number of treasure box items earned over the course of the simulation.
Sample Program Run
How many days will you run the simulation?
10
What was your overall behavior on day 1?
0
How many stickers did you earn on day 1?
3
What was your overall behavior on day 2?
0
How many stickers did you earn on day 2?
3
What was your overall behavior on day 3?
0
How many stickers did you earn on day 3?
1
What was your overall behavior on day 4?
0
How many stickers did you earn on day 4?
2
What was your overall behavior on day 5?
0
How many stickers did you earn on day 5?
3
At the conclusion of day 5, you received 2 treasure box item(s).
What was your overall behavior on day 6?
0
How many stickers did you earn on day 6?
3
What was your overall behavior on day 7?
0
How many stickers did you earn on day 7?
3
What was your overall behavior on day 8?
1
How many stickers did you earn on day 8?
2
What was your overall behavior on day 9?
0
How many stickers did you earn on day 9?
3
At the conclusion of day 9, you received 1 treasure box item(s).
What was your overall behavior on day 10?
0
How many stickers did you earn on day 10?
3
In total, you received 3 treasure box item(s).
Deliverables
Two source files:
1. cubbies.c for your solution to Problem A.
2. treasurebox.py for your solution to Problem B.
Restrictions
Although you may use other compilers and coding environments, your programs must run in IDLE
for the Python programs and Code::Blocks for the C/C++ programs.
Grading Details
Your program will be graded on both its
1) Correctness
2) Your programming style and use of white space.

