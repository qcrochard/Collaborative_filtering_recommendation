Recommendation using Collaborative Filtering:
===

#### Objective:
- Give 5 best movies recommendation to a user from a database of 'Users VS Movies' ratings (98% empty)

#### Model: 
- Factorization of user_item matrix (SVD-like) ignoring missing values (not used to build vectors in latent space).
- Then rebuilding user_item matrix with its best approximation, thus predicting missing values.
  See: http://surpriselib.com/

#### Notebook:
- First manually, using a simplistic model
- Then using Surprise library to use Simon Funk's Netflix prized model.
- Calculating RMSE
- Tuning model
- Making recommendation per users: 5 best movies
