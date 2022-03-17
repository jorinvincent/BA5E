In this assignment you will have to implement algorithm 5E from the book: Finding the highest scoring alignment of two strings. 

The assignment is available in Gradescope as: https://www.gradescope.com/courses/358896/assignments/1822267 (Links to an external site.) .  For additional details, you can also see problem BA5E on Rosalind: http://rosalind.info/problems/ba5e/ (Links to an external site.) .

For this assignment your code should expect two files: input and BLOSUM62.txt .

The input file will contain exactly 2 lines containing two amino-acid strings.  BLOSUM62.txt will contain the BLOSUM62 matrix:  BLOSUM62.txt  Download BLOSUM62.txt.

Your program must create a file called "output" which contains exactly 3 lines as shown below:

24
ELVISLIVES
ELVI--IVES
The first line contains the score of the alignment between the two sequences, using the gap penalty Sigma = 5, and the scores provided by the BLOSUM62 matrix.  The second and third lines contain the sequences provided in the input, in the same order, with gap (-) characters inserted to form the alignment.  Note that the two lines must have the same exact length after the gap characters are added.
