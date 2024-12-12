# Statistical Methods for Machine Learning: Homework Solutions

# Part 1: Visualizing Dyad and Image Compression with SVD
# - Load an image (e.g., from skimage.data) and compute its SVD.
# - Visualize dyads \( \sigma_i u_i v_i^T \).
# - Plot singular values and analyze their distribution.
# - Implement k-rank approximations of the image.
# - Plot the approximation error \( ||X - X_k||_F \) and compression factor \( c_k \).

# Part 2: MNIST Digit Classification with SVD
# - Load MNIST data (./data/MNIST.mat) and extract digits 3 and 4.
# - Split data into training and test sets.
# - Compute SVD for training matrices \( X_1 \) and \( X_2 \).
# - Classify digits by projecting onto spaces of \( U_1 \) and \( U_2 \).
# - Compute misclassification rates and analyze results for other digits.
# - Extend classification to 3 or more digits.

# Part 3: Clustering with PCA
# - Load MNIST dataset and reduce dimensionality with PCA.
# - Visualize clusters in 2D for specific digits (e.g., 0, 6, 9).
# - Calculate average distances from centroids (train and test sets).
# - Implement a centroid-based classification algorithm and compute accuracy.
# - Repeat for different values of \( k \) and analyze results.

# Repository Structure
# - `notebooks/`: Jupyter notebooks for all tasks.
# - `data/`: Dataset files required for the exercises.
# - `results/`: Output images and plots.

# How to Run
# 1. Clone this repository.
# 2. Install dependencies (`numpy`, `scipy`, `matplotlib`, `sklearn`).
# 3. Open the notebooks in `notebooks/` using Jupyter.
