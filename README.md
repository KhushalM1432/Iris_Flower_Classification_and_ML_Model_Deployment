## Iris Flower Classification & Machine Learning Model Deployment

## Data Science

### **Python | Machine Learning | Scikit-learn | Streamlit | Pandas | Joblib | Classification | Predictive Analytics**

### Project Overview

Developed a Python-based machine learning application for predicting Iris flower species using four botanical measurements.

The project integrates a previously trained classification model with an interactive Streamlit web application, allowing users to enter flower measurements and receive predicted species along with class probability scores.

The application demonstrates practical skills in machine learning model integration, model serialization, classification inference, web application development, and deployment.

## Business Problem

Machine learning models are valuable when their predictions can be accessed through practical applications rather than remaining confined to development notebooks.

For classification problems, users need an accessible interface to enter input data, generate predictions, and interpret model outputs.

This project addresses that need by connecting a saved classification model to a web interface that enables interactive flower species prediction.

## Project Objectives

- Develop an interactive Iris flower classification application.
- Integrate a trained machine learning model into a Python web application.
- Use four numerical features for species prediction.
- Load a serialized model using Joblib.
- Generate predictions using Scikit-learn's prediction interface.
- Display predicted classes and probability scores.
- Build an interactive interface using Streamlit.
- Demonstrate a deployable machine learning inference workflow.

## Project Highlights

1. **Machine Learning Classification:** Implemented an application that uses a trained classification model to predict Iris flower species based on numerical input features.

2. **Model Integration:** Loaded a previously saved machine learning model from a Joblib file, allowing predictions without retraining the model whenever the application starts.

3. **Feature-Based Prediction:** Used sepal length, sepal width, petal length, and petal width as the four input variables for classification.

4. **Interactive Streamlit Interface:** Developed a browser-based interface with numerical input fields and a prediction button.

5. **DataFrame Construction:** Converted user-provided measurements into a structured Pandas DataFrame with the feature names expected by the model.

6. **Classification Inference:** Used the model's `predict()` method to generate a predicted Iris flower class.

7. **Probability-Based Output:** Used `predict_proba()` to retrieve the model's estimated probabilities for each flower species.

8. **Prediction Visualization:** Displayed the predicted class, individual class probabilities, and Streamlit progress bars for easier interpretation.

9. **Model Serialization:** Integrated Joblib to load a persisted model from the project directory.

10. **Machine Learning Deployment:** Structured the application for deployment through Streamlit, demonstrating how a trained model can be made accessible through a web interface.

11. **Reusable Prediction Function:** Organized prediction logic into a Python function that accepts flower measurements and returns the predicted class and probability values.

## Model Evaluation & Performance Analysis

Relevant evaluation techniques for an Iris classification model include:

- Classification Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- Training and Testing Performance
- Prediction Probability Analysis

The deployed application displays predicted classes and probabilities. Numerical evaluation scores should be added only after verifying them in the model development notebook.

## Technologies & Skills

**Programming:** Python

**Machine Learning:** Scikit-learn, Supervised Learning, Multiclass Classification, Predictive Modeling

**Data Processing:** Pandas, NumPy

**Model Management:** Joblib, Model Serialization, Model Loading

**Web Application:** Streamlit, Interactive Input Forms, Prediction Display

**Data Visualization:** Matplotlib, Seaborn, Streamlit Progress Bars

**Deployment Concepts:** Model Integration, Web-Based Inference, Dependency Management, Application Deployment

**Business Analytics:** Predictive Classification, Automated Decision Support, Data-Driven Applications

## Dataset Description

The project uses the Iris flower classification problem, which involves predicting flower species from four numerical measurements.

### Input Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the flower's sepal |
| Sepal Width | Width of the flower's sepal |
| Petal Length | Length of the flower's petal |
| Petal Width | Width of the flower's petal |

### Target Variable

**Iris Flower Species**

The standard Iris dataset contains three flower categories:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The deployed model uses the four input measurements to generate a predicted class and corresponding probability scores.

## Application Architecture

**User Input → Streamlit Interface → Pandas DataFrame → Saved ML Model → Class Prediction → Probability Display**

### Workflow Description

1. The user opens the Streamlit application.
2. The application loads the saved machine learning model.
3. The user enters sepal length, sepal width, petal length, and petal width.
4. The application constructs a Pandas DataFrame from the input values.
5. The model generates a predicted species using `predict()`.
6. The model calculates class probabilities using `predict_proba()`.
7. Streamlit displays the predicted species and probability scores.

## Project Deliverables

- **`app.py`** — Main Streamlit application containing the input interface, model loading, prediction function, and probability display.
- **`notebook/`** — Project directory containing the saved model and associated notebook resources.
- **`notebook/model.joblib`** — Serialized machine learning model used by the application.
- **`requirements.txt`** — Python dependencies, including NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Joblib, Streamlit, and IPython Kernel.
- **`README.md`** — Project documentation.
- **`LICENSE`** — Apache 2.0 license.
- **`.gitignore`** — Git configuration for excluded files.

## Installation & Local Execution

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Verify the Model File

Ensure the trained model is available at:

```text
notebook/model.joblib
```

### 3. Run the Streamlit Application

```bash
streamlit run app.py
```

### 4. Generate Predictions

- Open the application in your browser.
- Enter the four flower measurements.
- Click the Predict button.
- View the predicted Iris species.
- Review the class probability scores and progress bars.

## Business Applications

The project demonstrates concepts applicable to:

- Automated classification systems.
- Machine learning model deployment.
- Interactive predictive analytics applications.
- Scientific and botanical data classification.
- Feature-based decision support systems.
- Classification model demonstrations.
- Web-based AI and machine learning prototypes.

The Iris dataset serves as a demonstration problem; the architecture can be adapted to other classification use cases with appropriately trained models.

## Business Recommendations

1. **Input Validation:** Validate measurement ranges and provide helpful messages when users enter unrealistic values.

2. **Model Evaluation:** Document classification metrics and test-set performance to establish model reliability.

3. **Prediction Interpretation:** Explain that displayed class probabilities are model estimates rather than guarantees.

4. **User Experience:** Improve the interface with feature descriptions, measurement units, and example inputs.

5. **Error Handling:** Add appropriate handling for missing model files, incompatible dependencies, and inference failures.

6. **Model Versioning:** Maintain documented model versions and preprocessing requirements to support reproducible deployments.

7. **Application Monitoring:** Monitor application availability, prediction errors, and response times when deploying the application for regular use.

8. **Future Enhancement:** Consider comparing multiple classification algorithms and documenting the selected model's evaluation results.

## Conclusion

This project demonstrates practical skills in **Python, Machine Learning, Scikit-learn, Multiclass Classification, Pandas, Joblib, Streamlit, and Machine Learning Model Deployment**.

By integrating a trained classification model into an interactive web application, the project showcases the ability to transform a machine learning model into a usable prediction interface.

The project highlights foundational competencies relevant to Data Scientist, Machine Learning Engineer, Python Developer, and AI Application Developer roles.

project app link - [https://iris-deployment-khushal1.streamlit.app/](https://iris-deployment-khushal1.streamlit.app/)
