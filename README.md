

# Iris Flower Classification 🌸  

## Overview  
This project demonstrates the use of **Logistic Regression** to classify iris flowers into three species (*Setosa, Versicolor, Virginica*) based on their sepal and petal dimensions. The **Iris dataset**, introduced by Sir Ronald Fisher in 1936, is one of the most famous datasets in data science and machine learning.  

With a straightforward approach, the Logistic Regression model achieves a perfect accuracy of **100%**, making it an excellent example of applying machine learning to a classic problem.  



## Features  
The dataset includes 150 samples, each with the following features:  
- **Sepal Length (cm)**  
- **Sepal Width (cm)**  
- **Petal Length (cm)**  
- **Petal Width (cm)**  

Each sample is categorized into one of the following species:  
1. Setosa
2. Versicolor  
3. Virginica  



## Objective  
The goal is to build a machine learning model using Logistic Regression that can:  
1. Accurately classify the species of iris flowers based on the input features.  
2. Achieve an accuracy of 100% on the test data.  



## Workflow  

### 1. **Data Exploration**  
- Load and inspect the dataset to understand its structure.  
- Visualize feature distributions using histograms and box plots.  
- Explore pairwise relationships using scatter plots and heatmaps to identify patterns.  

### 2. **Data Preprocessing**  
- Check for missing or inconsistent data.  
- Normalize the features to ensure better model performance.  
- Split the dataset into training and testing sets for evaluation (e.g., 80-20 split).  

### 3. **Modeling**  
- Train a Logistic Regression model on the training dataset.  
- Use the trained model to predict the species for the test data.  

### 4. **Evaluation**  
- Evaluate the model using metrics such as accuracy and confusion matrix.  
- Achieve a perfect accuracy score of **1.0 (100%)**.  



## Setup  

### Prerequisites  
Ensure you have the following installed on your system:  
- Python (≥3.8)  
- Required libraries:  
   ```bash  
  pip install numpy pandas matplotlib seaborn scikit-learn  
  ``` 

## Clone the Repository  
1. Clone the repository to your local machine:  
```bash  
  git clone  https://github.com/bhavishyashetty/Iris_Flower_Classification.git 
   cd Iris_Flower_Classification 
```

2. Run the classification code in your preferred Python environment (e.g., Jupyter Notebook, VS Code, or PyCharm).  

