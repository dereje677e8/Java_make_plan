# Java_word_problem_to_code
word problem question number 1.
_________________________________________
An integer is defined to be a Guthrie number if it is an element in the infinite sequence 1, 2, 4, 
7, 11, 16 … Note that 2-1=1, 4-2=2, 7-4=3, 11-7=4, 16-11=5 so for k>1, the kth element of the 
sequence is equal to the k-1th element + k-1. E.G., for k=6, 16 is the kth element and is equal to 
11 (the k-1th element) + k-1.
Write function named isGuthrie that returns 1 if its argument is a Guthrie number, otherwise it 
returns 0. So isGuthrie(11) returns 1, is Guthrie(22) returns 1 and isGuthrie(8) returns 0 .
The function signature is
   int isGuthrie (int n)
