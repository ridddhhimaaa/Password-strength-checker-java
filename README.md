📌 Password Strength Analysis Security Risk Scoring System
📌 Project Overview

This project is a Java based Password Strength Checker integrated with Data Science and Machine Learning analysis, following DevOps best practices.

The system evaluates password strength using rule based feature engineering, generates structured security data, performs exploratory data analysis and visualization using Python, and trains a machine learning model to classify password strength. GitHub version control, branching, and merging are used to manage development workflows.

📌 Objectives

Build a password strength checker using Core Java and Maven
Evaluate passwords using feature based scoring
Generate a structured dataset in CSV format for analysis
Perform data analysis, visualization, and ML modeling using Python
Demonstrate DevOps practices such as Git branching and merging
Maintain clean project structure and documentation

📌 Technologies Used
📌 Programming and Build

-Java JDK
-Maven

📌 Data Science and ML

-Python
-Pandas
-Matplotlib
-Scikit learn
-Jupyter Notebook

📌 DevOps and Tools

-Git and GitHub
-Command Line Windows
-Git branching and merging

📌 Project Structure
password-checker/

├── analysis/
│   └── password_analysis.ipynb

├── screenshots/
│   ├── maven_build.png
│   ├── cmd_run.png
│   ├── jupyter_dataframe.png
│   └── jupyter_graph.png

├── src/
│   └── main/
│       └── java/
│           └── com/example/
│               └── PasswordChecker.java

├── password_data.csv
├── pom.xml
├── .gitignore
└── README.md

📌 Java Application Logic

The Java application performs the following steps.
Accepts password input from the user
Extracts password features such as length, uppercase characters, digits, and special characters
Assigns weighted scores to each extracted feature
Classifies password strength as Weak, Medium, or Strong
Stores the results in a CSV file for analysis

📌 Feature Based Scoring Example
| Feature           | Weight |
| -------------------------- |
| Length            = 30     |
| Uppercase         = 15     |
| Lowercase         = 15     |
| Digit             = 20     |
| Special Character = 20     |

📌 Command Line Execution

The application is built using Maven and executed through the command line to evaluate password strength and generate data.

📌 Dataset Generation

Each execution appends one new row to password_data.csv. This dataset is later used for Data Science analysis and Machine Learning modeling.

📌 Data Science and Visualization

The generated dataset is analyzed using Pandas and visualized using Matplotlib to understand password strength distribution and feature impact.

📌 Machine Learning Model

Model used is a Decision Tree Classifier
Features include length, uppercase, digit, special character, and score
Target variable is password strength category
Purpose is to predict password strength based on extracted features

This demonstrates how rule based systems can be extended into predictive models.

📌 DevOps Practices Used

Git version control
Separate branch for ML analysis named ml analysis
Merging ML branch into main
Gitignore to exclude build artifacts and checkpoints
Clean commit history and structured repository

📌 Learning Outcomes

Java and Maven project structuring
Feature engineering for security analysis
Dataset creation and preprocessing
Data visualization and ML modeling
GitHub branching and merging workflow
End to end integration of DevOps and Data Science

📌 Future Enhancements

Add OWASP password policy rules
Improve ML model with larger datasets
Integrate Jenkins CI pipeline
Deploy the system as a REST API

📌 Author

Riddhima Rai
Engineering Student
Domain Data Science, DevOps, Machine Learning

📌 Conclusion

This project demonstrates how a traditional Java application can be enhanced with Data Science and Machine Learning techniques while following modern DevOps practices, making it suitable for academic evaluation and real world learning.

