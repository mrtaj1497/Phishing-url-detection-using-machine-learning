# Phishing URL Detection Using Machine Learning

## Project Overview

Phishing attacks are a common cybersecurity threat in which attackers use fraudulent URLs and websites to steal sensitive information from users.

This project focuses on detecting phishing URLs using Machine Learning techniques. It analyzes URL-related features and applies text preprocessing and classification algorithms to distinguish phishing URLs from legitimate URLs.

The project uses the **PhiUSIIL Phishing URL Dataset** and implements a Logistic Regression classification model with hyperparameter optimization.

## Project Components

This repository contains two main components:

| Component | Description |
|---|---|
| Jupyter Notebook | Machine learning implementation, data preprocessing, model training, and evaluation |
| UI Source Package | ZIP archive containing the user interface project files |

## Features

- Phishing and legitimate URL detection
- Exploratory Data Analysis (EDA)
- URL text preprocessing
- Tokenization and stemming
- Feature extraction using CountVectorizer
- Numerical feature analysis and correlation analysis
- Logistic Regression classification
- 5-fold cross-validation
- Hyperparameter tuning using GridSearchCV
- URL prediction for user-provided URLs

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud
- Pickle

## Dataset

**Dataset Name:** PhiUSIIL Phishing URL Dataset

The dataset contains URL-related information and numerical features used for phishing detection.

The notebook loads the dataset from Google Drive:

`PhiUSIIL_Phishing_URL_Dataset.csv`

Dataset file: [Add your Google Drive dataset link here]

Note: The dataset is not included directly in this GitHub repository.

## Machine Learning Workflow

1. Import libraries and load the dataset.
2. Explore dataset structure and statistical information.
3. Check missing values and target distribution.
4. Perform exploratory data analysis and visualization.
5. Remove selected unnecessary columns.
6. Encode the Top-Level Domain (TLD) feature.
7. Tokenize URL text using NLTK.
8. Apply Snowball stemming.
9. Extract text features using CountVectorizer.
10. Analyze numerical features and correlations.
11. Split the dataset into training and testing sets.
12. Train the Logistic Regression model.
13. Evaluate model performance.
14. Perform 5-fold cross-validation.
15. Optimize hyperparameters using GridSearchCV.
16. Test the model using a sample URL.
17. Save the trained preprocessing and classification pipeline.

## Repository Structure

```text
Phishing-url-detection-using-machine-learning/
│
├── Copy_of_Phishing_Web_URL_Detection.ipynb
│
├── phishing-url-ui.zip
│
├── README.md
│
└── .gitattributes
```

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/mrraju1212/Phishing-url-detection-using-machine-learning.git
```

### Step 2: Open the Notebook

Open `Copy_of_Phishing_Web_URL_Detection.ipynb` using Google Colab or Jupyter Notebook.

### Step 3: Upload the Dataset

Upload `PhiUSIIL_Phishing_URL_Dataset.csv` to your Google Drive and update the dataset path in the notebook if necessary.

### Step 4: Mount Google Drive

Run the following code in Google Colab:

```python
from google.colab import drive
drive.mount('/content/drive')
```

### Step 5: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud
```

### Step 6: Execute the Notebook

Run the notebook cells sequentially to perform data analysis, preprocessing, model training, evaluation, and URL prediction.

## UI Source Code

The UI source package is provided separately as:

`phishing-url-ui.zip`

Download the ZIP archive from the repository and extract it to access the UI project files.

## Future Improvements

- Integrate additional machine learning algorithms.
- Improve model performance through feature engineering.
- Develop a more user-friendly interface.
- Integrate real-time URL detection.
- Deploy the application as a web-based phishing detection system.

## Author

**Shyman Tarafdar Taj**

GitHub: [@mrraju1212](https://github.com/mrraju1212)

## License

This project is available for educational and research purposes. Add an appropriate license before allowing reuse or redistribution.
