#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n)
This is a linear equation the way that it is set up. The loop will continue to evaluate the number of times that n equals. So whatever n equals comes out to be the number of times that the loop is run. The bigger n is the more times the loop will run.

b) O(n log n)
This code is not quite linear. The bigger the input you enter, the more it continues to grow but not at the same rate as the numbers that you are entering. But it is also adding to the sum with each iteration which is where the first n of n log n comes from.

c) O(n)
This is another linear equation because as n (or bunnies) increases so does the output, and it increases at a constant rate.

## Exercise II

There is a building that has n # of floors. An egg can be dropped from any floor lower than f and survive. Once dropped from f or higher, the egg will break. Based on this problem, I assume that f will be closer to the first floor than the highest floor of the building. Therefore, if I start by dropping an egg from the first floor and it survives, I will move on to the second floor and reattempt. If the egg survives, I will continue to the next floor until the egg breaks. At that point I will know which floor number = f. This will minimize the total number of eggs dropped and only one will break - the one that determines floor f. This will result in a runtime complexity of O(n).
