# Introduction to C++

## Lab4 - Pointers and Arrays

Write a program to represent a noughts and crosses game. 

1. Use a two dimensional array of characters, with 3 rows and 3 columns, each cell in the array will contain 'X' or 'O'. Initially set each cell to contain '?'.
   Write a function to display the array. The function will have a prototype like
   ```
   void displayBoard( char [][3] board )
   ```
   (We need to define how many columns there are in the parameter, because of the pointer arithmetic we discussed in the class)

2. Now write a function that asks a user to play as 'X'. Ask them to enter two integers and use these as the coordinates of the element to set. Set the cell value accordingly.
The function will have a prototype like
   ```
   bool playX( char [][3] board )
   ```
   The function should return true if the cell was set correctly (take care, you cannot set a cell that has already been used!)

   Write a second function to do the same for a user to play as 'O'.

3. Write a main loop for the program, which will play the game. Repeatedly ask for X to play, then O. For the moment, simply run the main loop for a few iterations, to see that all the components work together.
