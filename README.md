# Predicting Box Office Revenue for Movies
1) Condensed JSON formatted multilabel text fields constituting 80% of the data utilizing python library “Abstract Syntax Trees”, optimizing data preprocessing.  

2) Transformed movie summary text using TFIDF into quantitative values, measuring the uniqueness of movie content.

3) Revamped multilabel and multiclass fields by generating dummy variables deploying MultilabelBinarizer and OneHotEncoding, creating model ready inputs. 

4) Assessed impact of a Director, Actor, Budget, etc. on the movie revenue, employing sci-kit learn ExtraTreesClassifier, yielding 5 prime features contributing 60% to Randomforest prediction with evaluation parameter RMSE equals 1.58.
