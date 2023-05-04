Download Link: https://assignmentchef.com/product/solved-csci1300-1310-quiz-3
<br>



Write a function that compares the elements of two arrays and returns the first index where the arrays are different. The function takes three arguments that are the two arrays to compare and the length of the arrays. You can assume that the arrays are the same size. If the arrays are the same, the function should return -1.

use the function header int arrayCompare(int firstArray[], int secondArray[], int arrayLength)

Examples:

int A[5] = {1, 2, 3, 4, 5} int B[5] = {1, 2, 3, 4, 5} int C[5] = {5, 4, 3, 2, 1}

Arrays A and B contain the same elements, so arrayCompare should return -1. Arrays A and C contain the same elements, but in a different order, so arrayCompare should return 0 since it is the first location where the array values are different.

#2

Write a function that takes two strings, compares their length, and returns the smaller of the two strings. If the strings are equal in length, return the string “no difference”. Use the function header:

string compareStrings(string first, string second)

Example 1:

string first = “hello” string second = “helloworld” compareStrings(first, second) will return the value “hello”.

Example 2:

compareStrings(“str1”,”str2”) will return “no difference” since they are the same length.