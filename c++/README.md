
The bubble sort is probably one of the easiest sorting algorithms 
to understand. The function sifts through the array swapping 
pairs of numbers over and over again until it is finally sorted.
When it makes it's first pass, it compares the first two numbers
(or elements) of the array. If the first number is greater than
the second number, it is swapped with that number. Then it 
compares the second and third numbers (or elements) of the array. 
If the second number is greater than the third, it is swapped with
that number. It continues down the line until it has gone through
the entire array. Then it makes another pass through it doing
the same thing. It makes a pass for each element. So if an array
has 8 elements, the array will be sifted through 8 times. 
The function takes 2 arguments. One is the array itself(int a[]). 
Two is the number of elements in the array(int n). This number 
is important because, as I said earlier, the array is to be sifted
through once for each element in the array.
