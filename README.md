# Computational Geometry Algorithm Visualization

This project aims to visualize various computational geometry algorithms, including convex hull algorithms such as brute force, Graham scan, Jarvis march, quick hull, and monotone chain, along with line intersection algorithms.

## Convex Hull

A convex hull is the smallest convex polygon that encloses a given set of points. It finds applications in various fields like computer graphics, image processing, and geographical information systems.

### Brute Force

The brute force method involves checking every possible combination of points to determine the convex hull. While straightforward, it's inefficient for larger datasets due to its high time complexity.

### Graham Scan

Graham scan is an efficient algorithm that finds the convex hull by sorting points based on their polar angles and iterating through them to construct the convex hull. It has a time complexity of O(n log n).

### Jarvis March

Jarvis march, also known as the gift wrapping algorithm, iterates through all points to construct the convex hull by selecting the next point with the smallest polar angle. It has a time complexity of O(nh), where n is the number of points and h is the number of points on the convex hull.

### Quick Hull

The quick hull algorithm employs a divide-and-conquer strategy to find the convex hull by recursively partitioning the points into subsets and finding the convex hulls of those subsets. It has an average-case time complexity of O(n log n) but can degrade to O(n^2) in the worst case.

### Monotone Chain

The monotone chain algorithm, also known as Andrew's monotone chain, sorts the points based on their x-coordinate and divides them into upper and lower chains. It then constructs the convex hull by merging these chains. It has a time complexity of O(n log n).

## Line Intersection

Line intersection algorithms determine whether two lines intersect and if so, where they intersect.

### Method 1: Orientation Based

This method determines the relative orientation of three points to check for line intersection. If the orientations of two line segments differ, they intersect. This approach has a time complexity of O(1).

### Method 2: Cross Product Based

The cross product based method involves calculating the cross product of vectors formed by the line segments and checking for collinearity. If the cross product is zero, the lines are collinear; otherwise, they intersect. It has a time complexity of O(1).

### Method 3: Parametric Representation

This method represents lines in parametric form and solves for the intersection point by equating the equations of the lines. It's suitable for lines represented in slope-intercept form or any other parametric representation. It has a time complexity of O(1).

## Conclusion

These algorithms play crucial roles in various computational tasks, and visualizing them can aid in understanding their inner workings and performance characteristics.
