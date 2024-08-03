# Breaking Bug - Machine Learning Repository

<img src="https://images.prismic.io/ieeemuj/Zqu58B5LeNNTxuyE_BreakingBugBanner.png?auto=format,compress" alt="Breaking Bug Poster">

## Table of Content
- [Introduction](#introduction)
- [Pre-requisites](#pre-requisites)
- [How to get started?](#how-to-get-started)
- [Setting up the project](#setting-up-the-project)
- [Project Information](#project-information)
- [Credits](#made-by-ieee-computer-society--manipal-university-jaipur)

### Introduction
This repository contains the backend code for the Breaking Bug event. The event is organized by IEEE Computer Society, Manipal University Jaipur.\

Breaking Bug is an electrifying virtual showdown for tech enthusiasts and coding maestros! An exciting and challenging event where participants step into the shoes of skilled developers and problem-solvers! In this unique competition, their mission is to identify and fix bugs in a GitHub repository across three diverse domains: Frontend, Backend, and Machine Learning (ML).


### Pre-requisites
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost


### How to get started?

- Download the code and dataset from the provided links.
- Set up your development environment with the pre-requisites listed above.
- Follow the steps mentioned in the [Setting up the project](#setting-up-the-project)  section.
- Use any platform or IDE to fix the bug, test, and train your model.
- After making the changes, push your code to your cloned repository.
- Submit the link to your updated repository or results through the specified form.


### Setting up the project

- Fork the repository by clicking on the `Fork` button on the top right corner of the page.

- Clone the repository in your local system.
```bash
git clone https://github.com/<your-github-username>/BreakingBug-ML.git
```

- Navigate to the project directory.
  ```bash
  cd BugBytes-ML
  ```

- Download the dataset `dataset.csv`.

- Open the `bugged_file.py` and review the code to identify and fix the bugs.

- Test and train your model using the dataset.

- After making the necessary changes, run the script to ensure everything works correctly.

- Push your changes to your cloned repository.

- Submit the link to your updated repository or results through the form link provided.


### Project Information

Here’s a revised summary focusing on the ML-related details:

Points Distribution

The maximum attainable points for this project are 1000. The points are distributed as follows:

| Difficulty Level | Points |
|------------------|--------|
| Very easy        | 20     |
| Easy             | 30     |
| Medium           | 40     |
| Hard             | 75     |
| Easter egg       | 100    |
| Total            | 1000   |

Here are the columns from the dataset, with their descriptions:

Dataset Columns

- **id**: Unique ID
- **age**: Age in years
- **sex**: Gender
- **dataset**: Location of data collection
- **cp**: Chest pain type
- **trestbps**: Resting blood pressure
- **chol**: Cholesterol measure
- **fbs**: Fasting blood sugar
- **restecg**: ECG observation at resting condition
- **thalch**: Maximum heart rate achieved
- **exang**: Exercise induced angina
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: The slope of the peak exercise ST segment
- **ca**: Number of major vessels (0-3) colored by fluoroscopy
- **thal**: Thalassemia
- **num**: Target [0 = no heart disease; 1, 2, 3, 4 = stages of heart disease]

Here’s the updated table without the "Best Hyperparameters" column:

Model Performance

| Model                   | Cross-Validation Accuracy | Test Accuracy |
|-------------------------|---------------------------|---------------|
| Logistic Regression     | 0.5115                    | 0.5109        |
| Gradient Boosting       | 0.6396                    | 0.5978        |
| KNeighbors Classifier   | 0.5767                    | 0.5870        |
| Decision Tree Classifier| 0.5840                    | 0.5761        |
| AdaBoost Classifier     | 0.6058                    | 0.5978        |
| Random Forest           | 0.6288                    | 0.6739        |
| XGBoost Classifier      | 0.6263                    | 0.6413        |
| Support Vector Machine  | 0.5877                    | 0.5870        |
| Naive Bayes Classifier  | 0.5780   <img width="1369" alt="Screenshot 2024-08-03 at 7 19 28 PM" src="https://github.com/user-attachments/assets/fb83b408-8702-4505-8aaa-839e2a2c3f60">
<img width="1371" alt="Screenshot 2024-08-03 at 7 20 47 PM" src="https://github.com/user-attachments/assets/49a9bc7f-ea3e-4412-bf4c-59dc7eec2a5f">
<img width="1195" alt="Screenshot 2024-08-03 at 7 24 31 PM" src="https://github.com/user-attachments/assets/59385399-4c36-4305-a398-bdd00024e555">
<img width="1356" alt="Screenshot 2024-08-03 at 7 32 14 PM" src="https://github.com/user-attachments/assets/e89a67dc-ba81-4e0e-8bbf-c4143f82c172">
<img width="742" alt="Screenshot 2024-08-03 at 7 38 37 PM" src="https://github.com/user-attachments/assets/2bf19801-0f74-4cde-a78a-494eaf7031a9">
<img width="1372" alt="Screenshot 2024-08-03 at 7 41 20 PM" src="https://github.com/user-attachments/assets/f6d475ad-1c07-4b4c-98ed-1435e5b6e5c4">
<img width="742" alt="Screenshot 2024-08-03 at 7 38 37 PM" src="https://github.com/user-attachments/assets/73d454f2-a167-4159-90a8-14cc648f495c">
<img width="1356" alt="Screenshot 2024-08-03 at 7 32 14 PM" src="https://github.com/user-attachments/assets/41c8c8da-cf99-4626-901e-00373b2dad08">
<img width="1094" alt="Screenshot 2024-08-03 at 7 29 38 PM" src="https://github.com/user-attachments/assets/168ed472-6248-441a-8651-73f0d669301c">
<img width="961" alt="Screenshot 2024-08-03 at 7 27 36 PM" src="https://github.com/user-attachments/assets/0f280fcb-ce30-4085-adf8-c7f2f2460c7f">
<img width="1371" alt="Screenshot 2024-08-03 at 7 20 47 PM" src="https://github.com/user-attachments/assets/dedd10f6-d08f-4bf8-80de-e0b1effcc697">
<img width="1369" alt="Screenshot 2024-08-03 at 7 19 28 PM" src="https://github.com/user-attachments/assets/4760caa3-cee9-4897-b120-f8d781262939">
<img width="1043" alt="Screenshot 2024-08-03 at 7 17 55 PM" src="https://github.com/user-attachments/assets/6598f2a9-4390-4f16-b87b-6888e17c54a7">
<img width="1352" alt="Screenshot 2024-08-03 at 7 16 26 PM" src="https://github.com/user-attachments/assets/48085398-bc96-4d34-8953-84d6fde06094">
<img width="1372" alt="Screenshot 2024-08-03 at 7 41 20 PM" src="https://github.com/user-attachments/assets/bfbbe6fe-601b-47fb-9e11-62d95776a714">
                 | 0.5435        |

Best Model: XGBoost Classifier  
Best Model Cross-Validation Accuracy: 0.6263  
Best Model Test Accuracy: 0.6413

## Made by IEEE Computer Society- Manipal University Jaipur
<br>
<img src="https://images.prismic.io/ieeemuj/Zqu58B5LeNNTxuyF_cs-logo.png?auto=format,compress" alt="IEEE CS MUJ Logo">
<br>
