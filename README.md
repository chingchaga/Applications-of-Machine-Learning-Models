1. Use logistic regression to predicted probability for all the data points in "quantum_spin_bit_meas.txt" and compare with the theoretical values.

2. Use the SVM regressor to model the intensity as function of pixel coordinate (row, column), i.e., I = I(row, column).

3. Load "SeaSurfaceTemperature_monthly_187001-202402.nc" and focus on the east Pacific tropical ocean covering latitude range [30 deg S, 30 deg N] and longitude range [-150 deg, -120 deg]. Use PCA to do a dimension reduction to represent the SST at east Pacific tropical ocean and compute the mean square errors.

4. Train a neural network to classify handwritten digit images provided by MNIST database. Build a neural network model using softmax activation to predict the probability of each of the 10 digits.



Builds a machine‑learning model to learn sea‑surface temperature as a function of time, latitude, and longitude from global monthly NetCDF data. It involves data preprocessing, train/validation/test splitting, hyperparameter tuning, and model evaluation using error metrics and residual analysis, the trained model is used to predict and visualize future monthly SST at Hong Kong through 2030. 
