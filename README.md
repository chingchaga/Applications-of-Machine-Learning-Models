1. File "quantum_spin_bit_meas.txt" contains two columns of data to be respectively the angle in degrees and the measurement output of the bit value. Use logistic regression to predicted probability for all the data points and compare with the theoretical values.

2. Create a 80x80 sub-image that captures the intensities by of two stars in the field. The goal is to use the SVM regressor to model the intensity as function of pixel coordinate (row, column), i.e., I = I(row, column).

3. Load "SeaSurfaceTemperature_monthly_187001-202402.nc" and focus on the east Pacific tropical ocean covering latitude range [30 deg S, 30 deg N] and longitude range [-150 deg, -120 deg]. Perform a PCA analysis to find out dominant feature patterns that varies with time, i.e. using time dimension as "sampling" index (row) and spatial dimensions (lat/lon) together as feature space (column). Use the first 5 principal components (PCs) to do a dimension reduction to represent the SST at east Pacific tropical ocean and compute the mean square errors of this approximation of using only 5 PCs.

4. Train a neural network to classify handwritten digit images provided by MNIST database. Build a neural network model using softmax activation to predict the probability of each of the 10 digits.
