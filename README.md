# Titanic Survival Prediction

A machine learning project that uses logistic regression to predict whether a passenger survived the Titanic disaster, based on various features such as age, sex, class, and fare.

## 📊 Dataset

This project uses the [Titanic dataset](https://www.kaggle.com/c/titanic/data), which includes passenger data such as:

- Passenger class (`Pclass`)
- Gender (`Sex`)
- Age
- Number of siblings/spouses aboard (`SibSp`)
- Number of parents/children aboard (`Parch`)
- Fare paid
- Port of embarkation (`Embarked`)
- Survival status (`Survived`)

## 🚀 Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales features.
- **Modeling**: Logistic Regression implemented using `scikit-learn`.
- **Evaluation**: Confusion matrix, classification report, accuracy score.
- **Visualization**: Heatmap of the confusion matrix for intuitive understanding of predictions.

## 🧠 Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- seaborn
- matplotlib

## 📁 Project Structure

```
├── titanic_prediction.py      # Main script with all functionalities
├── Titanic-Dataset.csv        # Dataset file (you need to provide this)
├── requirements.txt           # Python dependencies
```

## 🔧 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Make sure the dataset (`Titanic-Dataset.csv`) is in the same directory as the script or update the file path accordingly.

4. Run the script:
   ```bash
   python titanic_prediction.py
   ```

## ✅ Output Example

- Classification report with precision, recall, and F1-score.
- Confusion matrix visualization.
- Printed survival predictions for validation samples.

## 📌 Note

- Ensure the dataset path in the script is correct before running.
- If you're using a Jupyter notebook, you can adapt the script into cells easily.

## 📬 Contact

For any questions or feedback, feel free to reach out at [your-email@example.com](mailto:your-email@example.com) or open an issue.

---

**Made with ❤️ using Python and scikit-learn**
