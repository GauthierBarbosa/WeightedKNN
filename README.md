# Data-Driven KNN Modeling for Mixed Data: An Optimized Weighted Distance Approach


The repository related to this paper is structured into three primary directories, each designed for specific functions as outlined below:

-   **Datasets** : This directory includes all the datasets used in the Case Study detailed in the paper : 
    - The Ionosphere folder contains the metadata and the ionosphere.data file from [UCI Website](https://archive.ics.uci.edu/dataset/52/ionosphere).
    - The Steel_industry_data.csv contains Steel industry Current-related data, it is accessible on [Kaggle](https://www.kaggle.com/datasets/joebeachcapital/steel-industry-energy-consumption).
    - The houses-votes-84.csv containing 1984 Congressional Voting Records, taken from [UCI Website](https://archive.ics.uci.edu/dataset/105/congressional+voting+records).
    - The insurance.csv containing insurance price and characteristics, taken from [Kaggle](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset).
    - The Liver_disorder.csv containing Medical data related to Liver Disorder, available on [Network Repository](https://networkrepository.com/liver-disorders-bupa.php).
    - The pima-indians-diabetes.csv containing Medical data related to diabetes, taken from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
    - The servo.data containing servo-motor information, taken from [UCI Website](https://archive.ics.uci.edu/dataset/87/servo).

- **Results** : This directory contains all the results from the simulations using the 7 methods (Traditional KNN, Overlap, OF, Eskin, Gwknn and our proposed Model). It applies the method given in the paper related to this repository. It is organised as follows : 
    - The *10-Repetitions-Best-Results* folder contains the best result for each method and each dataset.
    - The *10-Repetitions-Rankings* folder contains the rankings after comparing the methods.
    - The *Raw_Results_by_Dataset_and_by_Method* folder contains Raw results (after some preprocessing in order to have some usable data) of the tests we ran on the datasets.

- **CodeSnippets** : This directory contains the notebook used to obtain the results from the previous directory.