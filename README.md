# Optimal-Matrix-Path

The purpose of the program is to use dynamic programming to find the path giving the largest
sum from the bottom row to the top row of a 2D matrix. The program keeps track of the penultimate index
for each entry from the row below and updates the row with the maximum sum that can be generated for
each element up to that point. This is done to reduce the number of computations done.

The program uses the Java Arrays, Stack, and Scanner libraries.
