# CSE 15L Lab Report 5
## Amber Tse A16776236 12/3/2023

Part1:

Student:

"I want to add a file to our lab3 repository called ```ShiftOver```that has a method, ```shiftRight```, that takes an integer array and shifts over the elements to the right by 1, replaces the first element with a 0, and deletes the last element. I wrote some tests for my method but they aren't passing. For the two tests that aren't passing, it says that the third element differs between the expected and the actual. Any help?"

![Image](lab5(1).png)

![Image](lab5(2).png)

![Image](lab5(3).png)

![Image](lab5(4).png)

![Image](lab5(5).png)


TA:

"In what direction does your for loop change the elements in your array?. I would try add a line in your shiftRight method that prints out the resulting array to see your output. You can do this by importing the Arrays package at the top of your ```ShiftOver.java``` file by adding ```import java.util.Arrays; ```. To print your array, add the line ```System.out.println(Arrays.toString(arr));``` to your shiftRight method, and run your ```shiftTest.sh``` bash file again."

Student:

"Thank you! The bash script made me realize that my for loop was copying the value of the second element to every spot on the array. My for loop was assigning new element values starting from the left and going to the right, which was the bug. I realized that the for loop should assign the elements of the array from right to left and not from left to right. To fix the bug, I changed the for loop to start at the end (right side) of the array and move to the left, this way I don't copy over the same value to each array index. All my tests passed now."

![Image](lab5(6).png)

![Image](lab5(7).png)

![Image](lab5(8).png)

![Image](lab5(9).png)


Part 2:

I found out that the terminal is more powerful than I thought, and you can do a lot jsut from the terminal. I didn't know you could create new directories, files, make edits to the files, etc. I also didn't know that you can use your terminal to commit new changes in your code to your github repository. I thought that the terminal was used mostly for compiling java code and running your methods, but there is a whole lot more you can do at the terminal.  

