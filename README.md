# DataCo-Supply-Chain-Data-Modelling



## Overview

This project utilizes a dataset obtained from Kaggle called [DataCo Marketing Analytics](link-to-dataset). The dataset contains approximately 1,80,000 rows and 53 columns, which were processed and analyzed to build three different models: a regression model to predict profit, and two classification models. The first classification model was designed to predict fraud transactions within the dataset, while the second classification model aimed to predict late deliveries.

## Dataset

The [DataCo Marketing Analytics](link-to-dataset) dataset serves as the foundation for this project. It consists of extensive information related to marketing activities and customer interactions. The original dataset underwent a thorough data cleaning and preprocessing phase to ensure the quality and integrity of the data.

## Methodology

1. Data Cleaning: The dataset was carefully cleaned to handle missing values, outliers, and inconsistencies. This step involved imputing missing values, removing duplicate entries, and correcting erroneous data.

2. Data Processing: Various data processing techniques were employed to transform the dataset into a suitable format for model training. This included feature scaling, one-hot encoding categorical variables, and handling imbalanced classes for classification models.

3. Regression Model: A regression model was built using a specific set of features to predict profit. This involved feature selection, model training using appropriate regression algorithms, hyperparameter tuning, and performance evaluation.

4. Classification Model 1: The first classification model aimed to identify fraud transactions. The dataset was labeled accordingly, and a comprehensive feature selection process was carried out. Classification algorithms were employed, followed by model training, hyperparameter tuning, and performance evaluation.

5. Classification Model 2: The second classification model focused on predicting late deliveries. Similar to the first classification model, relevant features were selected, and classification algorithms were applied. The model was trained, tuned, and evaluated using appropriate metrics.

## Project Structure

The project structure is organized as follows:

- **data**: Contains the dataset used in the project.
- **notebooks**: Jupyter notebooks containing code for data cleaning, preprocessing, model building, and evaluation.
- **models**: Saved model files generated during the training phase.
- **reports**: Reports and visualizations related to the project analysis and results.
- **README.md**: The main documentation file you're currently reading.

## Instructions

To replicate this project or utilize the models provided, follow these steps:

1. Clone the repository to your local machine using `git clone <repository-url>`.
2. Install the necessary dependencies mentioned in the `requirements.txt` file.
3. Run the Jupyter notebooks in the `notebooks` directory in the specified order to understand the project workflow and reproduce the results.
4. Access the trained models in the `models` directory if you wish to make predictions on new data.
5. Explore the `reports` directory for visualizations and analysis reports generated during the project.

## Acknowledgments

- Kaggle for providing the [DataCo Marketing Analytics](link-to-dataset) dataset.
- Open-source libraries and frameworks utilized in this project.

## License

Specify the license for your project if applicable.
