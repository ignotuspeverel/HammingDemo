# Report for hamming coding

All the detailed work is in the file **hamming.ipynb**. 

In the first part we encode the input data with the length of 1, 4 and 11. In these cases we will output 3, 8 and 15 bits for the data. We use the even checking and instead of do the xor we just calculate the 1 on the locations we want. By the function **hamming(str input)** we obtain the desire results.

![](.\img\result1.jpg)



In the second part we check the input whether it is correct as a hamming encoded message. The input length is 3, 7 and 15. We use E1, E2, E4 and E8 as the check bits. We also use the number of 1 on the locations we want to check out the data. By the function **hamming_check(str input)** we obtain the desire results.

![](.\img\result2.jpg)