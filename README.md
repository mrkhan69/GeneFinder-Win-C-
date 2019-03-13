# GeneFinder-With-C++
Biologists use a sequence of the letters A, C, T, and G to model a genome. A gene is a substring of a genome that starts after a triplet ATG and ends before a triplet TAG, TAA, or TGA. Furthermore, the length of a gene string is a multiple of 3, and the gene does not contain any of the triplets ATG, TAG TAA, or TGA. Write a program that prompts the user to enter a genome and displays all genes in the genome. If no gene is found in the input sequence, display "no gene is found".

Here Are Some Sample Runs:

<Output>
  Enter a Genome: TTATGTTTTAAGGATGGGGCGTTAGTT <enter icon>
  TTT
  GGGCGT
<Output>
  
<Output>
 Enter a Genome: TTATCTTT <enter icon> 
  No Gene Found
<Output>
