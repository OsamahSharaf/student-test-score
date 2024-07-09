Student Exam Score Prediction

This project aims to predict student exam scores in Math, Reading, and Writing using various machine learning techniques. The project includes data analysis, model development, evaluation, and the creation of an interactive user interface.

Project Objectives

Data Analysis:

Conduct thorough analysis of the student exam results dataset to understand key features and their distributions.
Model Development and Evaluation:

Develop and train predictive models using Support Vector Regression (SVR) for Math, Reading, and Writing scores.
Evaluate model performance using metrics such as Mean Squared Error (MSE) and cross-validation techniques.
User Interface Creation:

Design and implement an interactive user interface using Gradio to allow users to input student data and obtain predicted scores.
End-to-End Solution:

Integrate data analysis, model development, and user interface into a cohesive system to provide a comprehensive tool for predicting student exam scores.
Installation

To run this project, you need to have Python installed along with the following packages:

pandas
numpy
seaborn
matplotlib
sklearn
gradio

You can install these packages using pip:


pip install pandas numpy seaborn matplotlib scikit-learn gradio

Usage

Data Analysis:

The data analysis part involves loading the dataset, cleaning it, and performing exploratory data analysis (EDA) to understand the distribution of features and their relationships.
Model Development:

Train models using Support Vector Regression (SVR) for predicting Math, Reading, and Writing scores.
Evaluate the models using metrics like Mean Squared Error (MSE) and cross-validation.
Interactive User Interface:

Create an interactive interface using Gradio where users can input student data and get predicted scores for Math, Reading, and Writing.
How to Run

Clone this repository:

git clone https://github.com/yourusername/student-test-score-prediction.git
cd student-test-score-prediction
Open the Jupyter notebook student-test-score.ipynb to explore the data analysis and model development steps.

Run the Gradio interface:


python run_gradio.py

Project Structure

student-test-score.ipynb: Jupyter notebook containing data analysis and model development steps.
run_gradio.py: Script to run the Gradio interface for predicting student scores.
data/: Directory containing the dataset.
models/: Directory for saving trained models.
Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements

The dataset used in this project is sourced from [source].
Gradio for providing an easy-to-use library for creating interactive user interfaces.
