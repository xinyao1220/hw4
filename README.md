# hw4

1.How many lines are drawn each frame? In other words, how often does the for loop run?

38 lines

2. What do the first, second, and third appearances of the number 10 do in the code?

The first 10 is the x-coordinate of the first line; The second 10 is the X-coordinate of the last line (which is the width-10=390); The thirst line is the distance between each line.
  


1. How many times does the loop body run each frame, once the x and y arrays are full?

6 times

2. What are two ways of increasing the spacing between rings?

The first way is to change the 10 in i=i+10 which is in the loop body.
The secong way is to change the i in 1 + (x.length - i).

3. How can you make the ellipse trail longer?

change the number in x = x.slice(-50) and y = y.slice(-50).
