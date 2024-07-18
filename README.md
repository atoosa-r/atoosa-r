## 👋 Introduction

Hi there! I'm Atoosa Rashid, a Data Scientist with over 8 years of experience in CRM, sales, and banking. I recently graduated from a data science program and I bring a unique blend of industry knowledge and technical expertise. 

Some fun facts about me: I love coffee (usually alongside something sweet), hikes, yoga, and volunteering. 

Below is an example of my modeling skills demonstrated through a fun Python function that predicts the likelihood of me getting a sweet treat with each additional cup of coffee:

```python
import numpy as np
from sklearn.linear_model import LinearRegression

def predict_sweet_treats(coffee_cups):
    # Independent variable (number of coffee cups)
    X = np.array([[1], [2], [3], [4], [5]])
    
    # Dependent variable (likelihood of getting a sweet treat in %)
    y = np.array([94, 82, 63, 35, 15])
    
    # 1. Instantiate the model
    linear_regression_model = LinearRegression()
    
    # 2. Fit the model
    linear_regression_model.fit(X, y)
    
    # Predict the likelihood of getting a sweet treat
    predicted_likelihood = linear_regression_model.predict(np.array([[coffee_cups]]))
    
    return predicted_likelihood[0]

# Example:
coffee_cups = 3
predicted_likelihood = predict_sweet_treats(coffee_cups)
print(f'With {coffee_cups} cups of coffee, the likelihood of getting a sweet treat is {predicted_likelihood:.2f}%!')

```

Feel free to explore my work and reach out if you'd like to collaborate!

## 🛠️ Languages and Tools:

### Languages
<div>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/r/r-original.svg" title="R" alt="R" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" title="Bash" alt="Bash" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" title="HTML" alt="HTML" width="40" height="40"/>&nbsp;
</div>

#### 🔢 Data Analysis Libraries
`NumPy` | `Pandas` | `SciPy` | `Statsmodels`

#### 📈 Data Visualization
`Tableau` | `Matplotlib` | `Plotly` | `Seaborn`

#### 🤖 Machine Learning and Deep Learning
`Scikit-learn` | `TensorFlow` | `Keras` | `PyTorch` | `XGBoost` | `NLTK` | `BERT` | `Recommender Systems` | `Deep Learning`

#### 📊 Statistics
`Hypothesis Testing` | `A/B Testing` |  `Regression` | `Classification` | `Clustering` | `Time Series Forecasting` 

#### ☁️ Cloud Computing
`AWS` | `Spark` | `Hadoop` | `Hive` | `Docker`

#### 🔧 Version Control
`GitHub` | `Git`


## 📚 Data Science Projects:

### Enhancing Clothing Recommendations through Data-Driven Recommender Systems

Developed robust recommender systems by analyzing transactional data, customer information, and article details. Utilized advanced data preprocessing techniques and implemented multiple algorithms, including User-Item Collaborative Filtering, Matrix Factorization, and BERT-based systems, to enhance customer satisfaction and engagement.

For more details, visit the [repository](https://github.com/atoosa-r/BrainStationCapstone).

## 🔗 Let's Connect! 

<div id="badges">
  <a href="https://www.linkedin.com/in/atoosarashid/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:atoosarashid@gmail.com">
    <img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
  </a>
</div>

