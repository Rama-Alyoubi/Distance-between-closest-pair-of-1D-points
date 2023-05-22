# Distance-between-closest-pair-of-1D-points

for the Transform and conquer approach: The TnC_closest_pair_1D algorithm takes in an array of one-dimensional points and returns the minimum distance between any two points in the array, as well as the index numbers of the two closest points.
The algorithm uses a Transform and Conquer approach, which involves pre-sorting the points before applying the algorithm. This allows us to take advantage of the fact that the points are already sorted and avoid unnecessary comparisons.
The algorithm works by iterating through the sorted array of points and calculating the distance between adjacent points. We keep track of the minimum distance and the indices of the two points that are closest together.
As we iterate through the array, we update the minimum distance and the indices of the closest points if we find a pair of points that are closer together than the current closest pair.

for the Brute Force approach: The BruteForceClosestPair_1D algorithm is finding the closest pair of points in a one-dimensional array involves comparing every pair of points in the array and calculating the distance between them. The pair of points with the smallest distance is the closest pair.

The task at hand is to compare the efficiency of the Transform and Conquer algorithm with the Brute Force algorithm for finding the minimum distance between any two points in a one-dimensional array. This can be done using an empirical approach, which involves implementing both algorithms and running them on randomly generated different numbers of input points. The execution times for each algorithm are noted down and plotted as a function of the input size.
The resulting plot will show the execution times for both algorithms as a function of the input size. We can then analyze the plot to determine which algorithm is faster and why.

In general, we would expect the Transform and Conquer algorithm to be more efficient than the Brute Force algorithm, especially for larger input sizes. This is because the Transform and Conquer algorithm takes advantage of the fact that the points are already sorted and avoids unnecessary comparisons, whereas the Brute Force algorithm compares every pair of points in the array.
