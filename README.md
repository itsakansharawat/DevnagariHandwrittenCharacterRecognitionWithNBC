# Devanagari Handwritten Character Recognition using Naive Bayes Classifier

This project is focused on recognizing handwritten Devanagari characters using the Naive Bayes classifier. Devanagari is an abugida alphabet used in many languages, including Hindi, Marathi, and Nepali. Handwritten character recognition is an important task in machine learning, and it has many practical applications, such as digitizing handwritten documents.

## Dataset

The dataset used in this project is the Devanagari Handwritten Character Dataset, which can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset). The dataset consists of 92,000 images of Devanagari characters, divided into 46 classes (each class represents one character).

## Prerequisites

Before running the code, you need to install the following packages:

* Python 3.7 or higher
* NumPy
* Matplotlib
* Scikit-learn

You can install these packages using pip:

```python
pip install numpy matplotlib scikit-learn
```
## Running the Code

To run the code, follow these steps:

1. Download the dataset from the UCI Machine Learning Repository.
2. Extract the dataset to a folder called devanagari.
3. Clone this repository using the following command:

```python
git clone https://github.com/your-username/devanagari-handwritten-character-recognition.git
```

4. Navigate to the cloned repository:

```python
cd devanagari-handwritten-character-recognition
```

5. Run the naive_bayes.py file:

```python
python naive_bayes.py
```

This will train the Naive Bayes classifier on the dataset and test it on a separate test set. The accuracy of the classifier will be displayed on the screen.

## Results

After training the Naive Bayes classifier on the Devanagari Handwritten Character Dataset, we achieved an accuracy of 68.34% on the test set. This is a good result considering that we only used a simple classifier and did not perform any feature engineering.
![Handwritten Characters](https://user-images.githubusercontent.com/34977022/42726920-7314ee3a-87ba-11e8-8837-1c3dda7b4347.png)

## Conclusion

In this project, we showed that the Naive Bayes classifier can be used to recognize handwritten Devanagari characters with high accuracy. This project can be extended by using more advanced machine learning techniques or by using a larger dataset.
