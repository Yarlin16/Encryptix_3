
# Iris Species Classification

## Project Overview
This project uses machine learning to classify iris species based on their sepal and petal measurements. The model is trained on the Iris dataset, which includes measurements for the sepals and petals of three iris species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Dataset Overview
The dataset used in this project is the [Kaggle Iris dataset](https://www.kaggle.com/uciml/iris). It contains 150 samples from each of three species of Iris (Iris setosa, Iris virginica, and Iris versicolor).

- **Number of Instances:** 150
- **Number of Features:** 5
  - **sepal length (cm)**
  - **sepal width (cm)**
  - **petal length (cm)**
  - **petal width (cm)**
  - **species:** Target variable with three possible values (0: setosa, 1: versicolor, 2: virginica)

## Project Structure

The project is organized as follows:

1. **Data Loading and Preprocessing:**
   - Loading the dataset.
   - Splitting the dataset into training and testing sets.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing the relationship between features and species.

3. **Model Building and Evaluation:**
   - Training various machine learning models.
   - Evaluating model performance using metrics such as accuracy and confusion matrix.

4. **Prediction:**
   - Using the trained model to predict the species of new iris samples.

5. **Visualization:**
   - Presenting the results through graphs and charts for better understanding and interpretation.

## Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Results

- The final model's performance is summarized in terms of accuracy, precision, recall, and F1 score.
- Confusion matrix visualizations provide insights into the classification results.

## Conclusion

This project demonstrates the process of building a machine learning model to classify iris species. It covers data loading, preprocessing, exploratory data analysis, model training, evaluation, and prediction.

## Usage

To run this project, ensure you have the required libraries installed. You can install the dependencies using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Run the Jupyter notebook to execute the code step-by-step.

## Acknowledgements

- The dataset is provided by [Kaggle](https://www.kaggle.com/uciml/iris).
