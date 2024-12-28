# BackTracking-Line-Search

The assignment involves solving an unconstrained optimization problem using Gradient Descent methods, applying both exact line search and backtracking line search approaches.

# Code Structure

Code Implementation:

1. The problems are solved using Pyhton, by using the libraries such as numpy, matplotlib for numerical calculations and plotting the relevant graphs respectively.

2. Iterative sequences of solutions x_k are visualoized for both tasks. These plots demonstrate convergence trends for both line search methods.

# Problem Statement

The objective is to minimize the function as given:-

f(x) = (1/2) * x^T * P * x + q^T * x + log(e^(-2x_1) + e^(_x_2))

Where:

1. P = [[3,4], [4,6]]

2. q = [-2, 4]

3. Initial point: x_0 = [1, 2]^T

4. Stopping condition: ||∇f(x)|| < 10^-2

# Results

1. Observations on convergence rates for exact line search vs backtracking line search.

2. Differences in performance due to change in matrix P.

3. Exact line search achieves faster convergence for the original problem but is computationally intensive.

4. Backtracking line search balances computational cost with acceptable convergence.
