# Return_Array

Returning an array in C program is done by using pointers. In this program, two arrays of unknown size (size is input from the user) are two be created. This means the usual syntax of array definition will given an compilation error. We will have to use memory from the heap. 

After initializing both of these arrays of same sizes, the elements are taken as input. 

To add array elements a separate function is created. This means we have to transfer both the arrays. Since whole array transfer is not possible, the arrays are called by reference, i.e, the reference is the address of the first element of the array. 

The respective array element can be added easily. To store the result a new array has to created. But again the size is unknown so same procedure as for the two arrays is followed.

The new array is returned to the main function to print the elements. The address of the first element of the new array is returned and to collect it int the main a pointer variable is initialized.

And after getting this reference, the array can be printed.
