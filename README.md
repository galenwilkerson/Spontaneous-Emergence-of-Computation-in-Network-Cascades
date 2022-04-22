# Spontaneous-Emergence-of-Computation-in-Network-Cascades

The files here are gzipped Python 3.6 pickle (.pkl.gz) files.

Both correspond to runs of N = 10000 nodes.

# For the file ALTM_theta_results_k=2.pkl.gz

The number of possible inputs is k = 2.

The file contains a numpy array having shape:

(7, 10, 500, 16)  [theta_range x z range x num_trials x num_functions]

theta values are:

0., 0.16666667, 0.33333333, 0.5, 0.66666667, 0.83333333, 1.       

z values are:

0.000e+00, 5.000e-01, 1.000e+00, 4.000e+00, 1.600e+01, 6.400e+01, 2.560e+02, 1.024e+03, 4.096e+03, 9.999e+03

Each row of the file is a count of how often each function occurred in a single trial:

For example, the row

[9681,   73,    0, ...,    0,    0,    0]

means that function 0 was observed 9681 times, function 1 was observed 73 times, function 2 was observed 0 times, etc.


# For the file ALTM_theta_results_k=4.pkl.gz

The number of possible inputs is k = 4.

The file contains a numpy array having shape:

(1, 1, 500, 65536)  [theta_range x z range x num_trials x num_functions]

theta values are:
0       

z values are:
4
