📢 Advertising Click Prediction – Logistic Regression Project
A machine learning project to predict whether a user will click on an online advertisement based on their browsing behavior and demographic features.

📄 One-Line Description
Predict whether a user will click on an advertisement using logistic regression and user behavior data.

📁 Project Structure
Advertising Project.ipynb: Jupyter notebook containing all steps from data exploration to model evaluation.

Dataset: Included within the notebook or should be added separately (advertising.csv assumed).

🧠 Objective
Build a Logistic Regression model to classify whether or not a particular internet user clicked on an ad using available user and browsing data.

🛠️ Technologies Used
Python

Pandas – for data handling

Seaborn & Matplotlib – for data visualization

Scikit-learn – for preprocessing, modeling, and evaluation

📊 Features in Dataset
Daily Time Spent on Site: Minutes spent by user on website

Age: Age of the user

Area Income: Average income of user’s geographic area

Daily Internet Usage: Internet usage in minutes per day

Ad Topic Line: Ad headline

City, Country: Location of the user

Male: Binary gender feature

Timestamp: Time of ad interaction

Clicked on Ad: Target label (1 if clicked, 0 otherwise)

📈 Key Steps
Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Feature engineering (e.g., extracting hour from timestamp)

Splitting data into train/test sets

Training a logistic regression model

Evaluating model performance using confusion matrix and classification report

📎 How to Run
Clone/download this repository or open the .ipynb file in Jupyter Notebook.

Ensure you have the dataset advertising.csv in the same directory or update the path accordingly.

Run the notebook step by step to see the analysis and model in action.

✅ Outcome
A simple yet effective binary classifier trained on synthetic user data to understand how different behavioral features influence ad-click decisions.
