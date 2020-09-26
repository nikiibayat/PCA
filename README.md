# PCA and Eigenface
For this exercise, I used principal component analysis (PCA) to analyze face images in python. The data set faces.dat; each row represents an
image (400 images), and each column represents a pixel (64 × 64 = 4096 pixels).
(a) Display the 100th image.
(b) Remove the mean of the images, and then display the 100th image.
(c) Perform PCA on the mean-centered data matrix. 
(d) The last (i.e., 400th) eigenvalue is 0. Explain why.
(e) Based on the eigenvalues, determine the dimensionality of the data you want to keep
(i.e., how many principal components you want to keep), which accounts for most of the variance.
Explain your reason.
(f) Display the top-5 leading eigenvectors (corresponding to the top-5 largest eigenvalues)
in 5 figures.
(g) Display, respectively, the reconstructed 100th images using 10, 100, 200, and 399 principal components. 
