# compiler-optimization
Compilers are capable of generating sources codes in different ways depending on which opti- mizations are applied. The goal of this paper is to predict the execution time of code given the optimizations applied to it. Being able to predict the execution time of code given the optimiza- tions applied to it will allow one to choose the optimizations to apply to one’s code for maximum speedup without needing to actually execute the code. There are 7 different compiler flags so the total number of optimizations one can apply are 27 = 128 so in order to find the optimizations to apply to achieve the quickest execution time one would have to execute the code 128 times and then compare the execution times to choose the best optimizations. This can be problematic for code that takes a long time to execute as this would be very time consuming. To address this is- sue, this paper proposes the use of convolutional neural networks in order to predict a program’s runtime without actually running it.
