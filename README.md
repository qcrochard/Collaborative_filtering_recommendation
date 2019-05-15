Recommendation using Collaborative Filtering:
===

#### Objectives: 
- Factorization of user_item matrix (SVD-like) ignoring missing values (not used to build vectors in latent space).
- Then rebuilding user_item matrix best approximation, thus predict missing values.

#### How:
- Manually using simplistic model
- Then using Surprise library to use Simon Funk's Netflix prized model.
  See: http://surpriselib.com/
- Calculating RMSE
- Tuning model
- Make recommendation per users: 10 best movies
