# playwithPCA

Playing around with data to learn more about PCA

Author: Emily J King, https://www.math.colostate.edu/~king/

In this lab, different "approximately linear" data sets are generated and different aspects of principal component analysis are explored.

Current version: Matlab Live Script .mlx.  Download and use in Matlab.  
Coming soon: Jupyter Notebook.

Note: This lab does not make use of the Statistics and Machine Learning Toolbox, which has a pca function. 
If you look at the documentation of that function, then applying it to the data matrix X' yields the outputs coeff, 
which is the U of the SVD of the zero-centered data X_c, and score, which is V*S' of the SVD of the zero-centered data.
