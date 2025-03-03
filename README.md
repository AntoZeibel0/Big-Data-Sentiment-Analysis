The following repo contains three notebooks regarding **sentiment analysis** on Steam reviews.

The first notebook,_Reviews\_Data\_Prep.ipynb_, focuses on data exploration techniques, while preparing the data for the next stages in the ML pipeline (e.g. split the training data into chunks for incrementally training).

The second notebook, _Review\_without\_NaN.ipynb_, handles the imbalanced data (SMOTE), provides some NLP techniques, along with the actual incremental training. This stage uses the training chunks prepared earlier.

The third notebook, _Review\_All.ipynb_, does not handle imbalanced data, and it does not use the prepared chunks of training data. The purpose is to compare the result obtained in both presented instances.
