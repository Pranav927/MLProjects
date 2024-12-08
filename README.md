## End to end Machine Learning Project
# Predicting Target Math Score: An MLOps Project

## Objective
This project focuses on designing and implementing an end-to-end machine learning pipeline for predicting a target math score based on various input features. The workflow includes the following stages:

- Extracting, transforming, and processing data using Python scripts.
- Training machine learning models with optimized parameters to determine the best-performing algorithm.
- Building a robust data pipeline for ingestion, transformation, and model training.
- Creating reusable Python modules for custom exception handling, logging, and utility functions.

The following sections provide detailed insights into the dataset, technologies, and steps involved in the project.

---

## Table of Content
1. [Dataset Used](#dataset-used)
2. [Technologies](#technologies)
3. [Data Pipeline Architecture](#data-pipeline-architecture)
4. [Step-by-Step Implementation](#step-by-step-implementation)
   - [Step 1: Data Cleaning and Transformation](#step-1-data-cleaning-and-transformation)
   - [Step 2: Model Training and Evaluation](#step-2-model-training-and-evaluation)
   - [Step 3: Pipeline Integration](#step-3-pipeline-integration)
5. [Screenshots](#screenshots)

---

## Dataset Used
The dataset contains various features relevant to predicting a math score. These features include demographic, socio-economic, and prior academic performance indicators. Specific data cleaning steps ensured consistency and improved model performance.

---

## Technologies
The following technologies were used:
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, CatBoost
- **Pipeline and Orchestration**: Custom Python Scripts
- **Logging**: Python’s `logging` library
- **Web Framework**: Flask (for integration)

---

## Data Pipeline Architecture
The pipeline design integrates multiple stages:
1. **Data Ingestion**: Reads and preprocesses the raw data.
2. **Transformation**: Cleans and processes the data.
3. **Model Training**: Trains multiple algorithms and selects the best-performing model.
4. **Prediction Module**: Generates predictions based on trained models.

---

## Step-by-Step Implementation

### Step 1: Data Cleaning and Transformation
- Converted date columns into appropriate formats.
- Handled missing values using imputation techniques.
- Performed feature scaling and encoding for categorical variables.

Python Script: [data_cleaning.py](#)

---

### Step 2: Model Training and Evaluation
- Trained models such as CatBoost and RandomForest using hyperparameter tuning.
- Evaluated performance using metrics like R² and Mean Absolute Error (MAE).
- Saved the best model for deployment.

Python Script: [model_training.py](#)

---

### Step 3: Pipeline Integration
- Created a pipeline with reusable modules:
  - **Exception Handling**: Manages errors during execution.
  - **Logger**: Logs pipeline execution steps and issues.
  - **Utility Module**: Houses common functions used across the project.

Python Scripts:
- [exception_handler.py](#)
- [logger.py](#)
- [utils.py](#)

---

## Screenshots
### Data Cleaning and Transformation
![Data transformation](https://github.com/user-attachments/assets/6e2feb46-0ce6-4e2b-b16c-2ce788142bcb)


### Model Training
![Model Training](path/to/image2.png)

### Pipeline Logs
![Pipeline Logs](path/to/image3.png)

---

## Conclusion
This project showcases the implementation of an end-to-end MLOps pipeline for predicting math scores, emphasizing modularity and scalability. The tools and techniques utilized provide a blueprint for similar machine learning workflows.

---

## Future Work
- Integrating the pipeline with cloud services for scalability.
- Developing a dashboard for real-time predictions.

---

## Author
**Pranav927**

GitHub: [Pranav927](https://github.com/Pranav927/MLProjects)
