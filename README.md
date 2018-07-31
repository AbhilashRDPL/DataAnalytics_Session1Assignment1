# DataAnalytics_Session1Assignment1.1
DataAnalytics_Session1Assignment1.1
Problem 1
Que:-Prescriptive Analytics used to predict the future outcomes?
Ans:-True
Problem 2
Que:-Base R packages installed automatically?
Ans:-False
Problem 3
Que:-What is Recycling of elements in a vector?
Ans:-When applying an operation to two vectors that requires them to be the same length, R automatically recycles, or repeats, elements of the shorter one, until it is long enough to match the longer Vector.
Problem 4
Que:-Give an example of recycling of elements.
Ans:-Suppose we have two Vectors c(1,2,4) , c(6,0,9,10,13), where the first one is shorter with only 3 elements. Now if we multiply these two, we will get a warning message as follows.
> c(1,2,4) * c(6,0,9,10,13)
[1]  6  0 36 10 26
Warning message:
In c(1, 2, 4) * c(6, 0, 9, 10, 13) :  longer object length is not a multiple of shorter object length
