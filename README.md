# Wine Quality Prediction using Random Forest and Grid Search

This repository contains the code and resources for the "Wine Quality Prediction using Random Forest and Grid Search" project. The project aims to develop a machine learning model that predicts the quality of wines based on various chemical properties. The model utilizes the Random Forest algorithm and incorporates Grid Search for hyperparameter optimization.
Dataset

The dataset used for this project consists of a collection of wine samples along with their quality ratings. The dataset includes various chemical features such as acidity, pH levels, alcohol content, and more. The dataset is provided in CSV format and can be found in the data directory.
dataset link : https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/code?datasetId=4458&searchQuery=grid+
Requirements

To run the code in this repository, you need the following dependencies:

    Python (>= 3.6)
    scikit-learn (>= 0.24.2)
    pandas (>= 1.3.3)
    numpy (>= 1.21.2)

You can install the required dependencies using pip:

Usage

The project follows the following steps:

    Data Preprocessing: The data preprocessing step involves cleaning the dataset, handling missing values, and performing any necessary transformations. The code for data preprocessing can be found in the preprocessing.py file.

    Feature Selection: In the feature selection step, relevant features are selected from the dataset to train the model. The code for feature selection can be found in the feature_selection.py file.

    Model Training and Hyperparameter Tuning: The Random Forest model is trained using the selected features. Grid Search is applied to find the optimal hyperparameters for the model. The code for model training and hyperparameter tuning can be found in the model_training.py file.

    Model Evaluation: The trained model is evaluated using various evaluation metrics to assess its performance. The code for model evaluation can be found in the model_evaluation.py file.

    Performance Analysis: The performance of the model is analyzed and visualized using plots and metrics. The code for performance analysis can be found in the performance_analysis.py file.


## Results

The results of the project, including the trained model, evaluation metrics, and performance analysis, will be stored in the results directory.
## Contributing

Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests.
## License

This project is licensed under the MIT License.
## Acknowledgments

This project was developed as part of a machine learning course and is based on the concepts and techniques learned during the course. Special thanks to the course instructors and mentors for their guidance and support.
