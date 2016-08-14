#Read me file
#The following read me file specifies how to use the recommender system using spark

Download the code from this url. The specific files url are mentioned below:

complete_dataset_url = 'http://files.grouplens.org/datasets/movielens/ml-latest.zip'
small_dataset_url = 'http://files.grouplens.org/datasets/movielens/ml-latest-small.zip'

Download these files in the folder where the 'spark-recomender-engine-poc' has been installed. Make sure to create the folder 'datasets' inside the path where the
spark-recomender-engine-poc has been downloaded, and extract the zip files inside dataset.

Run the following command to execture the recommendation engine:

C:\softwares\spark-2.0.0-bin-hadoop2.7\spark-recommender-poc>C:\softwares\spark-2.0.0-bin-hadoop2.7\bin\spark-submit.cmd server.py