# 🎓 Student Placement Prediction Using Machine Learning

## 📌 Project Overview

Student Placement Prediction is a machine learning project that predicts whether a student is likely to be placed based on academic performance, technical skills, projects, internships, certifications, and Data Structures and Algorithms (DSA) scores.

The project uses a **Decision Tree Classifier** from Scikit-learn to demonstrate a basic machine learning classification workflow.

## 🎯 Objectives

* Predict student placement outcomes using machine learning.
* Explore the relationship between student profiles and placement status.
* Understand data preparation, feature selection, and classification.
* Demonstrate a beginner-friendly ML project using Python.

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* Scikit-learn
* Machine Learning

## 📊 Dataset Features

The project uses a sample dataset containing 30 student records.

| Feature        | Description                                 |
| -------------- | ------------------------------------------- |
| CGPA           | Student's academic performance              |
| Skills         | Technical skill rating                      |
| Projects       | Number of completed projects                |
| Internships    | Number of internships                       |
| Certifications | Number of certifications                    |
| DSA_Score      | Data Structures and Algorithms score        |
| Placed         | Target variable: 1 = Placed, 0 = Not Placed |

Student roll numbers and names are included in the dataset but are not intended to be used as prediction features.

## ⚙️ Machine Learning Workflow

1. Import the required Python libraries.
2. Create a sample student dataset using Pandas.
3. Convert the dataset into a DataFrame.
4. Select the relevant input features.
5. Define the placement status as the target variable.
6. Train a Decision Tree Classifier.
7. Evaluate the model using appropriate classification metrics.
8. Predict placement outcomes for new student profiles.

*Note: The workflow describes the intended project pipeline. Model training, evaluation, and prediction should be implemented and verified in the notebook before claiming these steps are completed.*

## 🚀 How to Run the Project

### Option 1: Google Colab

1. Open the notebook in this repository.
2. Download the `.ipynb` file.
3. Open [Google Colab](https://colab.research.google.com/).
4. Upload the downloaded notebook.
5. Run the notebook cells in order.

### Option 2: Run Locally

Install Python and the required libraries:

```bash
pip install pandas scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and execute its cells.

## 📦 Requirements

* pandas
* scikit-learn
* Jupyter Notebook (for local execution)

## ⚠️ Limitations

* The dataset contains only 30 sample student records.
* The sample data may not represent real-world placement patterns.
* Model performance on this dataset cannot establish how accurately the model would predict real student placements.
* Larger, representative datasets and proper model validation are necessary before practical use.

## 🔮 Future Improvements

* Use a larger, realistic student placement dataset.
* Compare Decision Tree, Logistic Regression, Random Forest, and other classifiers.
* Evaluate performance using accuracy, precision, recall, F1-score, and a confusion matrix.
* Build a simple web interface for entering student details and displaying predictions.
* Improve model validation and generalization.

## 👩‍💻 Author

**Pragna Sri**

GitHub: [@pragnasri09](https://github.com/pragnasri09)

---

⭐ If you find this project useful, consider starring the repository!
