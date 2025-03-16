Disease Prediction Based on Symptoms using Machine Learning

The "Disease Prediction Based on Symptoms" project aims to identify and predict diseases based on the symptoms provided by the user. With the growing number of new diseases and the emergence of dangerous variants in the 21st century, this tool provides early detection to help reduce fatalities by predicting the disease and suggesting timely medical intervention. This system employs Machine Learning algorithms such as Random Forest and Naive Bayes to make accurate predictions by comparing the results from both algorithms and selecting the one with the best accuracy.

The system is developed using Python, leveraging Tkinter for the user interface, providing an interactive experience for the user to input their symptoms and get disease predictions.

Features
User-Friendly Interface: Developed using Python's Tkinter library, the system offers an easy-to-use graphical interface for users to input symptoms, age, gender, and blood group.

Disease Prediction: Predicts possible diseases based on the symptoms entered by the user. The machine learning algorithms analyze the data and provide predictions with accuracy scores.

Multiple Algorithm Support: The system uses both Random Forest and Naive Bayes algorithms to compare their predictions and provide the most accurate diagnosis.

Accuracy Feedback: The system provides an accuracy score (ranging from 0 to 1) along with the disease prediction, helping users understand the reliability of the diagnosis.

Clear and Exit Buttons: Allows users to clear entered data and exit the application easily.

How It Works
Input Information: Users are prompted to enter their personal details such as name, age, gender, and blood group.

Symptom Selection: The user selects symptoms from a dropdown menu.

Prediction: Once the user inputs the symptoms, the system uses machine learning algorithms to predict the disease and displays the result along with the accuracy score.

Accuracy Comparison: The system compares predictions from both Random Forest and Naive Bayes, and presents the disease with the best accuracy.

Clear and Exit: The system provides buttons to clear the data or exit the application.

Machine Learning Algorithms
Random Forest: A powerful ensemble learning algorithm that uses multiple decision trees to make predictions. It works by aggregating predictions from each tree to increase accuracy and reduce overfitting.

Naive Bayes: A probabilistic algorithm based on Bayes’ theorem, it is particularly useful for classification tasks, and works well with smaller datasets and categorical inputs.

Architecture
Preprocessing: The data is first cleaned by removing noisy data, handling missing values, and ensuring that all data is complete and formatted properly.

Feature Extraction: The symptoms provided by the user are converted into a binary format (0s and 1s), which helps the model match the user’s input with historical data in the dataset.

Classification: The system uses machine learning algorithms (Random Forest and Naive Bayes) to classify the input symptoms and predict the corresponding disease.

Result Display: The predicted disease is displayed along with an accuracy score, allowing users to understand the confidence of the prediction.

Existing Systems vs Proposed System
Advantages of Existing Systems:
High accuracy rates (often above 90%).
Multi-algorithm support providing flexibility.
Some systems offer treatment recommendations based on the predicted disease.
User-friendly interfaces with easy symptom selection.
Disadvantages of Existing Systems:
Limited disease coverage.
Lack of transparency in decision-making (black-box issue).
Data privacy concerns.
Overreliance on algorithmic accuracy, which may not always be applicable in real-world scenarios.
Proposed System:
Uses both Random Forest and Naive Bayes for higher accuracy.
Provides transparency in algorithm selection by comparing two algorithms' results.
Offers a user-friendly interface with simple symptom selection.
Aims to predict a wide range of diseases, improving diagnosis accuracy.
Future Work
Expanded Disease Coverage: Adding more diseases and symptoms to the system for broader applicability.
Enhanced Privacy & Security: Ensuring robust encryption and privacy measures to protect user data.
Real-World Validation: Testing the system in real-world scenarios to ensure its accuracy and reliability.
Mobile App Integration: Extending the system to mobile platforms to reach a larger audience.
Technologies Used
Python: The primary language used for both backend processing and frontend UI development.
Tkinter: Python’s GUI library used to create the user interface.
Machine Learning Libraries: Scikit-learn for implementing Random Forest and Naive Bayes algorithms.
