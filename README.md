Welcome to the Latent Strain Analysis (LSA) code repository!

LSA was developed as a pre-assembly tool for partitioning metagenomic reads. It uses a hyperplane hashing function and streaming SVD in order to find covariance relations between k-mers. The code, and the process outline in LSFScripts in particular, have been optimized to scale to massive data sets in fixed memory with a highly distributed computing environment.

## Documentation ##
Documentation for LSA, including a "getting started" tutorial with accompanying test data, and step-by-step instructions for analyzing large collections, can be found at: http://latentstrainanalysis.readthedocs.org/

#### The lastest version of SciPy is broken for Python 2

These [changes](https://github.com/scipy/scipy/commit/e87cd85f440f02aca4d75fcccfb4b3d3782ca301) are needed to get SciPy functioning again.


