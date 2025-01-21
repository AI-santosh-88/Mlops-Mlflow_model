## PROJECT TITLE: 
### Iris Classification using Logistic Regression and Random Forest Models with MLflow for Experiment Tracking

### Project Description:
This project involves using two classification algorithms—Logistic Regression and Random Forest—to classify the Iris dataset, a well-known multi-class classification problem. The dataset is split into training and testing sets, and both models are trained and evaluated with a focus on underfitting by deliberately limiting model complexity (e.g., fewer iterations, regularization, and fewer trees in Random Forest). MLflow is utilized for experiment tracking, model logging, and model registration, ensuring transparency and version control of the machine learning models. The performance of the models is evaluated using accuracy and confusion matrices, and confusion matrix images are logged as artifacts for further analysis.
 
### Responsibilities:

#### 1. Data Preprocessing:
* Load the Iris dataset using sklearn.datasets.load_iris.
* Split the dataset into training and test sets using train_test_split.

#### 2.Model Training:
* Train two classification models: Logistic Regression and Random Forest, applying hyperparameters to induce underfitting (e.g., limiting iterations, increasing regularization, reducing tree depth).

#### 3.Model Evaluation:
* Evaluate models using accuracy and confusion matrices.
* Visualize and save confusion matrix plots as artifacts.

#### 4.Experiment Tracking and Model Management:
* Set up an MLflow experiment for tracking model parameters, metrics, and artifacts.
Log key parameters and metrics such as model type, hyperparameters, and accuracy.
Log models in MLflow and register them for version control and easy access.
Handle potential errors during model registration and loading.

#### 5.Visualization:
* Generate confusion matrix heatmaps using seaborn and matplotlib and save them as images.
* Ensure that the confusion matrix images are logged into MLflow as artifacts.

### Insights:

#### 1.Underfitting Impact:
* Both models were deliberately underfitted by adjusting hyperparameters (e.g., limiting iterations for Logistic Regression and reducing the number of trees and depth for Random Forest).
* This underfitting led to lower model accuracy, demonstrating the importance of finding the optimal complexity to balance underfitting and overfitting.

#### 2.Experiment Tracking with MLflow:
* Using MLflow for experiment tracking, model logging, and model registration provided a streamlined process for monitoring experiments, tracking metrics, and comparing models.
* MLflow allowed the seamless integration of model artifacts (e.g., confusion matrix images) and ensured that both models could be version-controlled and reused.

#### 3.Model Performance:
* Logistic Regression and Random Forest both showed lower performance compared to typical defaults, which was expected due to the underfitting setup. The accuracy scores and confusion matrices provided insight into the models' misclassifications.

#### 4.Model Registration and Management:
* The use of MLflow's model registry allowed for efficient model versioning, facilitating the management and comparison of models over time.
  
#### Summary:

This project highlights the application of two popular machine learning algorithms (Logistic Regression and Random Forest) for solving the Iris classification problem, with a focus on managing model complexity to induce underfitting. MLflow was leveraged throughout the project to manage experiments, log models, and track performance metrics and artifacts such as confusion matrix visualizations. This approach ensures transparency, reproducibility, and efficient management of models throughout the development lifecycle.




  


