# Enhanced Intrusion Detection for IoT: Utilizing Neural Network-based Weighted Classes for Handling Imbalanced Data

This project aims to solve the imbalance of classes within the dataset while providing a multi-output prediction model. It includes data processing, analysis, balancing techniques, and a multi-output neural network for data training. 

# Steps to Execute the Code
Step 1: Load the Dataset
Ensure you have the Bot-IoT dataset downloaded and available in your working directory. If not, you can download it from the Bot-IoT dataset repository.

Step 2: Combine Data Scenarios
Run the Bot_IoT_combine_data_scenarios.ipynb notebook to combine several scenarios of the Bot-IoT dataset. This notebook merges multiple datasets into a single dataset for further processing.
1.Open Bot_IoT_combine_data_scenarios.ipynb in Google Colab or Jupyter Notebook.
2.Execute all cells to combine the datasets.

Step 3: Data Preprocessing
Apply the BoT_IoT_preprocessing.ipynb notebook for data preprocessing steps including handling missing values, null values, mixed data types, and categorical data columns.

Open BoT_IoT_preprocessing.ipynb in Google Colab or Jupyter Notebook.
Execute all cells to preprocess the dataset.
Step 4: Neural Network-Based Detection
Execute the Enhanced_Intrusion_Detection_for_IoT_Neural_Network_based_Imbalanced_Data_Handling_and_Feature_Reduction.ipynb notebook. This notebook combines cost-sensitive learning trained with a multi-output neural network to predict both the category and subcategory classes of the data.

Open Enhanced_Intrusion_Detection_for_IoT_Neural_Network_based_Imbalanced_Data_Handling_and_Feature_Reduction.ipynb in Google Colab or Jupyter Notebook.
Execute all cells to train the neural network and make predictions.

