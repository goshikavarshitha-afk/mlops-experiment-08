# Experiment 08: GitHub Actions CI Workflow

## Aim
To automate the execution of a Machine Learning project using GitHub Actions.

## Description
This project demonstrates Continuous Integration (CI) by automatically running a Machine Learning program whenever code is pushed to GitHub or a pull request is created.

## Technologies Used
- Python
- Scikit-learn
- Pandas
- GitHub
- GitHub Actions
- Visual Studio Code

## Machine Learning Model
**Decision Tree Classifier**

The Iris dataset is used to train and evaluate the classification model.

## Project Structure
```text
mlops-experiment-08/
├── ml_project.py
├── requirements.txt
├── README.md
└── .github/
    └── workflows/
        └── ml_workflow.yml
```

## How to Run Locally

1. Install Python 3.11.
2. Install the required libraries:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Run the program:

   ```bash
   python ml_project.py
   ```

## GitHub Actions Workflow
The workflow automatically:
1. Checks out the repository.
2. Sets up Python 3.11.
3. Installs the required dependencies.
4. Executes the Machine Learning program.
5. Displays the model accuracy in the workflow logs.

## Expected Output
```text
ML Project Executed Successfully!
Model: Decision Tree Classifier
Accuracy: [actual accuracy]% 
```

The accuracy depends on the program's execution result.

## Result
Successfully developed a GitHub Actions CI workflow to automate the execution of a Machine Learning project.

## Author
B.Tech Artificial Intelligence and Machine Learning Student
