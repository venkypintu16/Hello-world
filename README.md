#Assignment 2
#Code to calculate mean for the provided values
#Testing of the code is below with output.

> assignment2 <- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22)
> myMean <- function(assignment2) { return(sum(assignment2)/length(assignment2)) }
> myMean(assignment2)
[1] 19.25

Explanation:
• The above R code defines a vector assignment2 and then calculates the mean of the values in this vector using a function named myMean. The detailed explanation of the code is provided below :

•	assignment2 <- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22): This line creates a vector named assignment2 with the given set of numeric values. The c() function is used to create a vector. 

•	myMean <- function(assignment2) { return(sum(assignment2) / length(assignment2)) }: This line defines a function named myMean that takes a parameter assignment2. Inside the function, it calculates the mean by dividing the sum of the vector assignment2 by its length.

•	myMean(assignment2): This line calls the myMean function with the vector assignment2 as an argument and gives the mean calculated value as an output.

•	The output of the mean calculation is printed: [1] 19.25, which is the mean of the values in the assignment2 vector.

•	References:

•	for vectors: https://www.w3schools.com/r/r_vectors.asp

•	for functions: https://www.w3schools.com/r/r_functions.asp

•	for sum() and length(): https://www.geeksforgeeks.org/sum-function-in-r/
