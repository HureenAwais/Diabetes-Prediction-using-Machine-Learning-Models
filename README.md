# Diabetes-Prediction-using-Machine-Learning-Models
This project predicts diabetes status using machine learning models trained on Nhanes dataset, which consists of clinical, demographic, lifestyle and examination features.

## Workflow

- **Problem defination:** Definig tye objective of developing a clinically relevant diabetes prediction model.
- **Data collection:**  Importing and loading the dataset.
- **Exploratory Data Analysis(EDA):** Understanding and visualising the dataset using statistical  descriptions and graphical representations.
- **Data split:** Data split in training, validation and testing sets.
- **Data preprocessing:** Data imputations, handling data anamolies and class imbalance using smote to prepare data for model training.
- **Feature selection:** Selecting relevant features using XGBoost and SHAP Analysis to improve model performance 
- **Base model training:** Training various base models on training dataset.Trained base models are RF, XGBoost, LightGBM, CatBoost,
SVM, Logistic Regression, and DNN
- **Hyperparameter Tunning:** Hyperparameter tunning using 5 fold cross validation.
- **Stacking ensemble :** Various ensemble models including Voting, Bagging, Boosting and hybrid stacking model were built and tested on test set.
- **Performance evaluation:** Used F1-score, Recall, Precision, Accuracy, and AUROC to
evaluate models
- **Web interface:** Real-time diabetes prediction Interface  was built via Gradio using a best performing model.

## Dataset
The dataset used in this project comes from the NHANES (National Health and Nutrition Examination Survey) provided by the Centers for Disease Control and Prevention (CDC). This dataset includes a wide range of health and nutrition measurements to predict diabetes.
