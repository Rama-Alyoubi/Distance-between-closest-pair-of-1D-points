# Distance-between-closest-pair-of-1D-points
for the Transform and conquer approach: The TnC_closest_pair_1D algorithm takes in an array of one-dimensional points and returns the minimum distance between any two points in the array, as well as the index numbers of the two closest points.
The algorithm uses a Transform and Conquer approach, which involves pre-sorting the points before applying the algorithm. This allows us to take advantage of the fact that the points are already sorted and avoid unnecessary comparisons.
The algorithm works by iterating through the sorted array of points and calculating the distance between adjacent points. We keep track of the minimum distance and the indices of the two points that are closest together.
As we iterate through the array, we update the minimum distance and the indices of the closest points if we find a pair of points that are closer together than the current closest pair.

for the Brute Force approach: The BruteForceClosestPair_1D algorithm is finding the closest pair of points in a one-dimensional array involves comparing every pair of points in the array and calculating the distance between them. The pair of points with the smallest distance is the closest pair.
