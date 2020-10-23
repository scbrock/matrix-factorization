# Matrix Factorization - Movie Recommender
In this project, I use matrix factorization to create movie recommendations. The program is in the Jupyter notebook "Matrix Factorization Recommender.ipynb".

## Movie Lens Small dataset
100,000 ratings and 3,600 tag applications applied to 9,000 movies by 600 users. Please see https://grouplens.org/datasets/movielens/ for more information.

## implementation 
Matrix factorization was completed using gradient descent to optimize the factorization of the ratings matrix into a user matrix and a movie matrix, where each user or movie contains a number of latent factors.  

## Results
The algorithm suggests the top predicted ratings for each user; however, the results do not contain the existing highly rated movies by a given user, so more investigation needs to be done.

## Conclusion
We can observe the reconstruction error diminishing over each epoch, but the reconstruction error achieved is not sufficient to consistently provide good recommendations. Further investigation into a stronger GPU is required to allow an increase in the number of epochs and to create higher dimension user and movie matrices.
