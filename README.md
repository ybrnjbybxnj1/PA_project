# PA_project
Algorithm, parallelization method: K-means clustering

To reproduce the results just run all cells from the notebook, at the results section you will see difference between paralleled algo and non-paralleled one, data is produced automatically.

Parallel part: computation of distances between points and centroids, partial sums and counts for updating centroids.

Figure with speedup calculations is available at the results section of the notebook and below.

![speedup_plot](https://github.com/user-attachments/assets/176a7aff-7ba6-4f47-9eb4-d9342a113df0)

As it can be seen, there is an improvement in speedup compared to the non-parallel version due to the the workload distribution across more processing units.
