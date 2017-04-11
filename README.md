# pdi-weka

This repository addresses two classificaiton problems via Decision Tree[J48] algorithm. One  jobs and transformation from PDIClient~Spoon7.0.0.1[Pentaho Data Integration] with Weka3.8.1.

1. Predict from a structured data [Diabetes]
2. NLP[ie English] based sentimentc classification from Movie reviews [dataset - https://www.cs.cornell.edu/people/pabo/movie-review-data/]

Each problem is designed as below.
One PDI job calling two transformations; one transformation creating the model form Weka Knowledge Flow [kfml] from train data set; another transformation performing Weka Scoring on previously learnt model for a test data set. Both Training and Test data sets are supplied.

Download and enjoy classificaiton via PDI-Weka!
