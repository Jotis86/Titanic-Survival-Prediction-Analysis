# 🚢 Titanic Dataset Analysis

## 🎯 Objective

The objective of this project is to analyze the Titanic dataset to predict passenger survival using machine learning techniques. We aim to identify the most relevant features influencing survival and evaluate the accuracy of the predictive model. This analysis helps us understand the factors that contributed to survival during the Titanic disaster.

## 🛠️ Functionality

This project performs the following functions:
1. 📂 Loading and Merging Datasets: Load the training and test datasets and combine them for a comprehensive analysis.
2. 🔍 Data Exploration and Cleaning: Explore the dataset to understand its structure, handle missing values, and select relevant features.
3. 🔢 Encoding Categorical Variables: Convert categorical variables into numerical values for model training.
4. 🧠 Training a Random Forest Model: Train a Random Forest classifier to predict passenger survival.
5. 📊 Model Evaluation: Evaluate the model’s performance using accuracy, classification report, and confusion matrix.
6. 🔮 Making Predictions: Predict survival for new test data and integrate the predictions into the dataset.
   
## 🧰 Tools Used
- Pandas: For data manipulation and analysis.
- Matplotlib and Seaborn: For data visualization.
- Scikit-learn: For implementing the Random Forest model and evaluating its performance.

##🛠️ Development Process
- 📚 Importing Libraries: Import the necessary libraries for data analysis and modeling, including pandas, matplotlib, seaborn, and scikit-learn.
- 📥 Loading Data: Load the training and test CSV files from the specified paths.
- 🔗 Merging Datasets: Combine the training and test datasets into a single DataFrame using pd.concat.
- 🔍 Data Exploration: Display the first few rows of the combined dataset and generate a concise summary, including data types and non-null values.
- 🧹 Data Cleaning: Handle missing values by imputing the median for Age and Fare, and the mode for Embarked. Verify that there are no remaining missing values.
- 🔢 Encoding Variables: Encode the Sex and Embarked columns into numerical values using mapping.
- ✂️ Splitting Data: Split the data into training and testing sets using train_test_split.
- 🧠 Training the Model: Create and train a Random Forest classifier with the training data.
- 📊 Evaluating the Model: Evaluate the model’s performance using accuracy, classification report, and confusion matrix.
- 🔮 Making Predictions: Create a DataFrame with new test data, make predictions using the trained model, and add the predictions to the DataFrame.

## 📈 Results
- Model Accuracy: The Random Forest model achieved an accuracy of XX% (replace with actual value). This indicates the proportion of correctly predicted instances out of the total instances.
- Classification Report: A detailed classification report showing precision, recall, and F1-score for each class, providing insights into the model’s performance for each category.
- Confusion Matrix: The confusion matrix shows the number of true positives, false positives, true negatives, and false negatives, helping to understand the model’s performance in detail.

## 📊 Visualizations
- The following visualizations were created to explore and understand the data:
   - 📊 Boxplot of Age by Survival
   - 📊 Boxplot of Fare by Passenger Class
   - 📊 Bar Plot of Survival by Number of Siblings/Spouses Aboard
   - 📊 Bar Plot of Survival by Number of Parents/Children Aboard
   - 📊 Histograms of Age and Fare Distribution
   - 📊 Scatter Plot of Age vs. Fare
   - 📊 Pair Plot of Numerical Features
   - 🧪 Model Evaluation Graphics

- In addition to standard metrics, the following graphics were used to evaluate the model:
   - 📊 Feature Importances in Random Forest
   - 📊 Confusion Matrix
   - 📊 ROC Curve
   - 📊 Distribution of Predictions

## 🧪 Manual Testing
- Manual testing was conducted to verify the correct implementation of each step, from data loading to prediction generation. It was ensured that there were no missing values and that the predictions were reasonable. This involved checking the data at each stage and validating the outputs.

## 🗂️ Project Structure
- The project is organized as follows:
   - data/: Contains the CSV files used (train.csv and test.csv).
   - notebooks/: Contains the Jupyter Notebook with the code (titanic_analysis.ipynb).
   - README.md: This README file with detailed information about the project.

## 🏁 Conclusion
- The project demonstrated the ability to predict the survival of Titanic passengers with acceptable accuracy using a Random Forest model. The most relevant features influencing survival were identified, and the model’s performance was thoroughly evaluated. This analysis provides valuable insights into the factors that contributed to survival during the Titanic disaster.

## 📧 Contact
- If you have any questions or would like to get in touch, please contact me at: jotaduranbon@gmail.com
