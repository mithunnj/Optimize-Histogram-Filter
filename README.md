# Optimize-Histogram-Filter

Leveraged my understanding of how the CPU and RAM works in a computer system to optimize the Histogram filter using C++. This resulted in  in more than a 6x decrease in execution time from 353.288 milliseconds to 51.232 milliseconds for 10000 iterations of the program. I used techniques like removing dead code, optimizing if statements and for loops, removing the use of extra variables, passing memory intensive variables by reference to the program’s functions, reserving space in memory for large vector sets, utilized the stack to store variables rather than in the heap inside the RAM, and declared static variables where necessary to improve efficiency. 

Program Details from tests:

Number of iterations: 10000,
Duration milliseconds initialize beliefs: 41.072,
Duration milliseconds sense: 56.133,
Duration milliseconds blur: 147.857,
Duration milliseconds normalize: 57.904,
Duration milliseconds move: 50.322,
Original total: 353.288,
New Total: 51.232
