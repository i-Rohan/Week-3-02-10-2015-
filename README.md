# Week-3-02-10-2015-

# HALL9000 (Easy)

Convert a number to palindrome by using simple addition, if it is not already a palindrome.  
<br>
Input:  A number <br>
<br>
Output:  Print the number of rounds of addition it took to make the number palindrome along with the new palindrome number.   
<br>
Sample Input: 
57 <br>
Sample Output: 
<br>
57 becomes a palindrome after 2 steps and the new number is 363 

<br> 
Sample Input: 76
<br>
Output: 76 becomes a palindrome after 2 steps and the new number is 484

<br> 
Sample Input: 23
<br>
Output: 23 becomes a palindrome after 1 step and the new number is 55




# JARVIS (Hard) 

Langford Pairing <br> 
Wikipedia Link: https://en.wikipedia.org/wiki/Langford_pairing <br>
Write a program to print out a Langford pairing for order n. However, instead of printing numbers, print capital alphabets, and use their index (like A is 1, B is 2, C is 3….. Z is 26) to compute the apartness between 2 alphabets. 

Example for n = 3. 
There are only 2 possible solutions 
<br>

<br> CABACB 
<br> BCABAC 

<br> Langford pairing only exists when the order is a multiple of 4, or one less than a multiple of 4.

For orders which would produce a lot of outputs print any 7 outputs. 
Orders >20 produce trillions of outputs, so we would be checking for maximum order of 7. 
