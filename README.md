# Detection of Learning Disability System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Evaluation](#models-and-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Detection of Learning Disability System is a machine learning-based project aimed at identifying learning disabilities in students using various classification models. This system evaluates the performance of different algorithms to determine the most effective model for detecting learning disabilities with limited data.

## Features
- Preprocessing of input data
- Training and testing of multiple machine learning models.
- Evaluation of model performance using metrics such as accuracy, precision, recall, F1 score, and kappa score
- Cross-validation to ensure model robustness
- Detailed performance reports and visualization

## Installation
To install and run the Detection of Learning Disability System, follow these steps:

1. Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/detection-of-learning-disability.git](https://github.com/GaddamVarshith/Detection_of_Learning_Disability_System.git)
    cd detection-of-learning-disability
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare your dataset and ensure it is in the correct format.
2. Modify the configuration parameters if needed (e.g., paths to data files, model hyperparameters).
3. Run the main script to start the training and evaluation process:
    ```bash
    python main.py
    ```

## Models and Evaluation
The system uses various classification models to detect learning disabilities, including:

- Support Vector Machine (SVM)
- Random Forest
- Naive Bayes (Gaussian)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

### Performance Metrics
The models are evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Kappa Score
- Log Loss (if applicable)

### Cross-Validation
To ensure the reliability of the results, cross-validation is performed, and the mean cross-validation score is reported.

## Results
The results of the model evaluations will be displayed in the console and saved in the `results` directory. These include performance metrics for each model and cross-validation scores.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out if you have any questions or need further assistance!
