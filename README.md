# Student Performance Classification System

This miniproject is a Python-based machine learning system for analyzing and classifying student performance into **High (H)**, **Medium (M)**, or **Low (L)** categories using multiple classification algorithms.

It provides both data visualization and prediction capabilities based on a dataset containing student behavioral and demographic information.

---

## 📊 Features

- **Interactive Visualizations**:
  - Class distribution by Gender, Grade, Topic, Semester, Nationality, Section, etc.
- **Machine Learning Models**:
  - Decision Tree
  - Random Forest
  - Perceptron
  - Logistic Regression
  - MLP (Neural Network)
- **Custom Input Prediction**:
  - Allows user to input student details to predict performance class using all 5 models.

---

## 🧠 Dataset

The system uses a dataset named `AI-Data.csv` which includes the following columns (among others):

- `gender`
- `NationalITy`
- `PlaceofBirth`
- `GradeID`
- `SectionID`
- `Topic`
- `Semester`
- `Relation`
- `raisedhands`
- `VisITedResources`
- `AnnouncementsView`
- `Discussion`
- `ParentAnsweringSurvey`
- `ParentschoolSatisfaction`
- `StudentAbsenceDays`
- `Class` *(Target Variable)*

---

## 🛠️ Installation

### Requirements

- Python 3.x
- pip (Python package manager)

### Install Dependencies

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```
Here's a sample `README.md` file for your project that includes a clear description, installation instructions, usage guidelines, and functionality overview:

---

## ▶️ Usage

1. Place the `AI-Data.csv` file in the same directory as the script.
2. Run the Python script:

```bash
python student_performance.py
```

3. Choose from the menu to visualize data or run ML models.
4. Optionally, test custom input to predict student performance class.

---

## 📈 Models & Accuracy

The following models are trained and evaluated:

| Model               | Accuracy (Sample Output) |
| ------------------- | ------------------------ |
| Decision Tree       | \~X.XXX                  |
| Random Forest       | \~X.XXX                  |
| Perceptron          | \~X.XXX                  |
| Logistic Regression | \~X.XXX                  |
| MLP Classifier      | \~X.XXX                  |

*Note: Accuracy may vary depending on data and random state.*

---

## 🧪 Example Prediction

After training, you can input custom student values such as:

* Gender
* Grade
* Raised Hands
* Visited Resources
* Parent Satisfaction
* Absence Days
  ...and more

The system will output predictions from all 5 models.

---

## 🧹 TODO / Suggestions

* Replace manual slicing with `train_test_split`
* Improve input handling (validate and automate feature processing)
* Integrate GUI (e.g., Streamlit)
* Save trained models for later use

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## 🙋‍♂️ Author

* Developed by : Rishi Patel
* For academic and research use.

```

