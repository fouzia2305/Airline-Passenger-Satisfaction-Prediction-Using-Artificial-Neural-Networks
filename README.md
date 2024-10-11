# Airline Passenger Satisfaction Prediction Using Artificial Neural Networks (ANN)

## Project Overview
This project aims to classify airline passengers as "satisfied" or "neutral or dissatisfied" based on various factors related to their travel experience using Artificial Neural Networks (ANN). The insights from this project can guide airlines to improve areas impacting passenger satisfaction, thereby enhancing customer experience and retention.

## Dataset
- **Source:** Historical passenger data consisting of 129,880 records.
- **Features:** 25 features including:
  - Demographic details (Gender, Age)
  - Travel details (Customer Type, Type of Travel, Class, Flight Distance)
  - Service ratings (Inflight wifi service, Food and drink, Seat comfort, etc.)

## Key Responsibilities

### Data Preprocessing
- Handled missing values and removed duplicate entries.
- Encoded categorical variables using `OneHotEncoder`.
- Scaled numerical features using `StandardScaler`.
- Addressed outliers in key features to ensure robust model performance.

### Exploratory Data Analysis (EDA)
- Conducted detailed numerical and categorical data analysis.
- Visualized distributions and relationships using histograms, box plots, and count plots.
- Analyzed correlations between features to understand their impact on passenger satisfaction.

### Model Development
- Built an ANN model with three hidden layers (512, 256, 128 neurons) and ReLU activation functions.
- Implemented the Adam optimizer and binary cross-entropy loss function.
- Achieved recall scores of 0.757 and accuracy scores of 0.892 on the test set.

### Comparative Analysis
- Compared ANN performance with traditional machine learning models: Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM).
- Evaluated models based on accuracy, recall, precision, and F1 scores.

## Challenges Faced
- Handling imbalanced classes between satisfied and dissatisfied passengers.
- Optimizing hyperparameters for both ANN and traditional models to improve performance.
- Addressing overfitting during ANN training through validation and model checkpoints.

## Results & Conclusion
- The ANN model achieved significant recall and accuracy, outperforming traditional models in recall but slightly trailing Random Forest in overall accuracy.
- The comparative analysis demonstrated the strength of deep learning in capturing complex patterns in passenger satisfaction data.

## Technologies Used
- Python
- TensorFlow/Keras
- Pandas
- NumPy
- Matplotlib/Seaborn
- Scikit-learn


