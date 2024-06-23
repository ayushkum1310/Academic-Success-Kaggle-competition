
# Academic Success Multi-Class Prediction

This project aims to predict academic success using multiple machine learning models, including CatBoost, LightGBM, XGBoost, and Random Forest, and then combining them using a Voting Classifier.

## Dataset

The dataset for this project comes from a competition and includes various features related to students' demographics, academic records, and socioeconomic indicators.

- Train Data: `/kaggle/input/playground-series-s4e6/train.csv`
- Test Data: `/kaggle/input/playground-series-s4e6/test.csv`
- Original Data: `/kaggle/input/acadmic-compitition-swag/data.csv`

## Libraries Used

- `numpy`
- `pandas`
- `sklearn`
- `seaborn`
- `matplotlib`
- `catboost`
- `xgboost`
- `lightgbm`
- `optuna`
- `warnings`

## Project Structure

1. **Loading and Merging the Dataset:**
   - Merging training and original datasets to create a comprehensive dataset.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing the distribution of features and their relationship with the target variable.

3. **Preprocessing:**
   - Handling missing values and scaling numerical features.

4. **Model Training:**
   - Splitting the data into training and testing sets.
   - Training individual models: CatBoost, LightGBM, XGBoost, and Random Forest.
   - Combining models using Voting Classifier for better performance.

5. **Hyperparameter Tuning:**
   - Using Optuna for hyperparameter tuning (commented out in the script).

6. **Final Model Prediction:**
   - Predicting the target variable for the test dataset and saving the results.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/academic-success-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd academic-success-prediction
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook or script:
   ```bash
   jupyter notebook
   ```

5. Upload the final predictions to Kaggle or your preferred platform.

## Results

- The final model's performance on the test data is evaluated using classification metrics like precision, recall, and F1-score.

## Conclusion

This project demonstrates the effectiveness of ensemble learning in predicting academic success by combining multiple models to achieve better performance.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Kaggle for providing the datasets.
- The authors and contributors of the libraries used in this project.

---

Made with ❤️ by Ayush Kumar  
Data Scientist
```

