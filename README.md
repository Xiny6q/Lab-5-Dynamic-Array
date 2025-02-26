Download link :https://programming.engineering/product/lab-5-dynamic-array/


# Lab-5-Dynamic-Array
Lab 5: Dynamic Array
Dynamic.cpp
In the starter code below, you will ﬁnd the stub of a function called ReadNumberSequence. Follow the Todo instructions to complete the function and the program that calls it.
This lab is a simple example of dynamic allocation of a single dimension array of integers. The test cases are designed to make sure that nothing in the program is hard-coded but is instead read from the stdin (cin).

Directions

Using the starter code below, follow the ToDo directions. This lab has you use dynamic allocation to create and populate an array.

/*

ToDo: Build a function that reads a sequence of integers from input to fill a dynamically allocated array.

Store the items and return a pointer to the array.

For example, if the length is 3, and the numbers are 123 345 99 then the array returned will be of size 3, and stores values 123, 345 and 99.

@param size: upon return, stores the size of the array @return the pointer pointing to the array

*/

int * ReadNumberSequence (int & size)

{

int * array = NULL; // create an array.

// the ptr to the array will be returned

//initialize the pointer to NULL

do {

cout <<“Enter the length of the number sequence:”;

cin >> size;

} while (size <= 0);

// Todo: Write a statement to allocate memory for the array.

// Note: we know the value of size only at run time, so we need to DYNAMICALLY

// Todo: write a loop to read size # of int from input, and store in the array

return array;

}

// ToDo: Complete the program
int main()

{

// Todo: declare necessary variables

// Todo: call the ReadNumberSequence function to read a sequence of numbers

// Todo: write a loop to display the elements in the array returned

// Todo: free the array returned by ReadNumberSequence

return 0;

}

Sample Output

Enter the length of the number sequence: 3
Enter 3 number of elements to store in the array: 123 345 99

123

345

99
