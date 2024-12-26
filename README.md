# PA_project
Algorithm, parallelization method: K-means clustering

To reproduce the results just run all cells from the notebook, at the results section you will see difference between paralleled algo and non-paralleled one, data is produced automatically.

Parallel part: computation of distances between points and centroids, partial sums and counts for updating centroids.

Figure with speedup calculations is available at the results section of the notebook and below.

![speedup_plot](https://github.com/user-attachments/assets/2b1855f8-ce43-41a3-9aba-8280e011a054)

As it can be seen, there is an improvement in speedup compared to the non-parallel version due to the the workload distribution across more processing units.
