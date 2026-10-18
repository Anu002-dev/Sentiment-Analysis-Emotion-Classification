# Sentiment-Analysis-Emotion-Classification


<div align="center">

  <h1>Sentiment Analysis – Emotion Classification</h1>

  <p>
    A Machine Learning project to classify emotions in text comments
    using TF-IDF, Naive Bayes, and Support Vector Machine.
  </p>

  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikitlearn" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Status">

</div>

<hr>

<h2>📌 Project Overview</h2>

<p>
  This project uses machine learning techniques to classify text comments
  into three emotion categories: <strong>Anger, Fear, and Joy</strong>.
  The text data is cleaned and transformed into numerical features using
  TF-IDF before training and evaluating two classification models.
</p>

<h2>🎯 Objectives</h2>

<ul>
  <li>Load and preprocess the text dataset.</li>
  <li>Perform text cleaning, tokenization, and stopword removal.</li>
  <li>Convert text into numerical features using TF-IDF.</li>
  <li>Train Multinomial Naive Bayes and Support Vector Machine models.</li>
  <li>Compare model performance using accuracy and F1-score.</li>
</ul>

<h2>🛠️ Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>NLTK</li>
  <li>Scikit-learn</li>
  <li>Google Colab / Jupyter Notebook</li>
</ul>

<h2>⚙️ Methodology</h2>

<ol>
  <li>
    <strong>Data Preprocessing:</strong>
    Converted text to lowercase, removed punctuation and unnecessary
    characters, tokenized comments, and removed stopwords while preserving
    important negation words.
  </li>
  <li>
    <strong>Feature Extraction:</strong>
    Used TF-IDF to transform text comments into numerical feature vectors.
  </li>
  <li>
    <strong>Model Training:</strong>
    Trained Multinomial Naive Bayes and Linear Support Vector Machine models.
  </li>
  <li>
    <strong>Evaluation:</strong>
    Compared models using accuracy, precision, recall, and weighted F1-score.
  </li>
</ol>

<h2>📊 Model Performance</h2>

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Weighted F1-score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Multinomial Naive Bayes</td>
      <td>89.06%</td>
      <td>89.06%</td>
    </tr>
    <tr>
      <td><strong>Linear SVM</strong></td>
      <td><strong>94.02%</strong></td>
      <td><strong>94.02%</strong></td>
    </tr>
  </tbody>
</table>

<h2>🏆 Results and Conclusion</h2>

<p>
  Linear SVM achieved an accuracy of approximately 94.02% and a weighted
  F1-score of approximately 94.02%, outperforming Multinomial Naive Bayes.
  Based on these evaluation results, Linear SVM was the better-performing
  model for classifying the three emotion categories in this dataset.
</p>

<h2>📁 Project Structure</h2>

<pre>
sentiment-analysis-emotion-classification/
│
├── Sentiment_Analysis.ipynb
└── README.md
</pre>

<h2>🚀 How to Run</h2>

<ol>
  <li>Clone or download this repository.</li>
  <li>Open <code>Sentiment_Analysis.ipynb</code> in Google Colab or Jupyter Notebook.</li>
  <li>Upload the dataset and update its file path if required.</li>
  <li>Run the notebook cells in order to train and evaluate the models.</li>
</ol>

<h2>👩‍💻 Author</h2>

<p>
  Created as a machine learning project focused on text emotion
  classification.
</p>

<hr>

<div align="center">
  <p><em>Sentiment Analysis using Machine Learning</em></p>
</div>
