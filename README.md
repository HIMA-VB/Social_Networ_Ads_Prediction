# Social_Networ_Ads_Prediction


```markdown
# Decision Tree Classifier for Social Network Ads

This repository contains Python code for training a Decision Tree classifier to predict whether users of a social network will purchase a product based on their age, gender, and estimated salary. The dataset used is the "Social_Network_Ads.csv."

## Contents

1. **Data Loading and Preprocessing:**
    - The code loads the dataset from the `Social_Network_Ads.csv` file and extracts features (age, gender, and estimated salary) and labels (purchase decision).
    - Label encoding is applied to convert the gender column into numeric values.
    - The data is split into training and testing sets using scikit-learn's `train_test_split`.
    - Feature scaling is performed using standardization with `StandardScaler`.

2. **Model Training:**
    - A Decision Tree classifier is trained with the criterion set to 'entropy' to measure the quality of splits and the random state for reproducibility.

3. **Model Evaluation:**
    - The code evaluates the model's performance using metrics such as accuracy, precision, recall, and F1-score.
    - A confusion matrix is also generated to visualize the model's performance.

4. **Results:**
    - The results are printed to the console, including the confusion matrix, accuracy score, precision score, recall score, and F1 score.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/decision-tree-social-ads.git
   ```

2. Navigate to the project directory:
   ```bash
   cd decision-tree-social-ads
   ```

3. Run the Python script to train the Decision Tree model and evaluate its performance:
   ```bash
   python decision_tree_social_ads.py
   ```

4. View the results in the script's output, which include metrics like accuracy, precision, recall, and F1-score.

## Dependencies

Ensure you have the required Python libraries installed. You can install them using the following commands:

```bash
pip install numpy
pip install matplotlib
pip install pandas
pip install scikit-learn
```

## Data

The dataset is loaded from the `Social_Network_Ads.csv` file. Make sure you have the dataset available in the project directory or specify the correct file path in the code.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This code demonstrates the use of a Decision Tree classifier for predicting social network users' purchase decisions based on their age, gender, and estimated salary. You can adapt and modify it for similar classification tasks or experiment with different machine learning algorithms.

If you have any questions or encounter any issues, please feel free to open an issue or contact the project maintainers.

Happy classifying social network users' purchase decisions!
```
