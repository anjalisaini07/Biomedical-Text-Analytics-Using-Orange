# Biomedical Text Analytics Using Orange Data Mining

A machine learning and natural language processing (NLP) project focused on biomedical text classification using Orange Data Mining. This project demonstrates text preprocessing, TF–IDF vectorization, dimensionality reduction, clustering, supervised learning, and prediction of unseen biomedical abstracts.

---

# Project Overview

Biomedical literature is growing rapidly, making manual analysis difficult and time-consuming. This project builds a complete NLP and machine learning workflow in Orange for automated biomedical text analytics and research-paper categorization.

The workflow combines:

* Text preprocessing
* TF–IDF feature extraction
* Principal Component Analysis (PCA)
* Cosine distance computation
* Hierarchical clustering
* Supervised classification
* Prediction on unseen biomedical abstracts

The project was implemented entirely using the visual workflow environment of Orange Data Mining without coding.

---

# Dataset

The dataset contains biomedical research abstracts collected from PubMed-related sources and categorized into multiple scientific domains.

## Categories Used

* Deep Learning
* COVID-19
* Human Connectome
* Virtual Reality
* Brain–Machine Interfaces
* Electroactive Polymers
* PEDOT Electrodes
* Neuroprosthetics

## Dataset Statistics

* Total labeled abstracts: 400
* Categories: 8
* Abstracts per category: 50
* Additional unseen abstracts: 10

---

# Tools & Technologies

* Orange Data Mining
* NLP & Text Mining Add-on
* TF–IDF Vectorization
* PCA (Principal Component Analysis)
* Hierarchical Clustering
* Logistic Regression
* Random Forest
* Naive Bayes
* Neural Network (MLP)

---

# Workflow

1. Import biomedical abstracts
2. Preprocess and clean text
3. Convert text into TF–IDF vectors
4. Reduce dimensionality using PCA
5. Compute cosine distances
6. Perform hierarchical clustering
7. Train machine learning models
8. Evaluate model performance
9. Predict categories of unseen abstracts

---

# Text Preprocessing

The following preprocessing operations were applied:

* Tokenization
* Lowercasing
* Stop-word removal
* Lemmatization
* Punctuation removal
* Number removal

These steps improved text quality and enhanced machine learning performance.

---

# Feature Extraction

TF–IDF (Term Frequency–Inverse Document Frequency) was used to transform biomedical abstracts into numerical vectors.

## TF–IDF Benefits

* Captures domain-specific terminology
* Reduces importance of common words
* Works efficiently for biomedical text classification
* Generates high-dimensional sparse vectors

---

# Principal Component Analysis (PCA)

PCA was applied to reduce the dimensionality of TF–IDF vectors.

## PCA Findings

* PC1 explained approximately 2.8% variance
* First 20 components captured ~25% cumulative variance
* First 30 components captured ~32% cumulative variance

PCA improved visualization and reduced computational complexity.

---

# Clustering Analysis

Hierarchical Agglomerative Clustering with cosine distance identified semantic relationships among biomedical domains.

## Observations

* COVID-19 abstracts formed tight semantic clusters
* PEDOT electrodes and electroactive polymers grouped strongly
* Neural engineering domains showed moderate overlap
* Biomedical topics displayed meaningful semantic structure

---

# Machine Learning Models Evaluated

| Model                | Accuracy |
| -------------------- | -------- |
| Logistic Regression  | 83.8%    |
| Neural Network (MLP) | 81.2%    |
| Random Forest        | 78.7%    |
| Naive Bayes          | 59.8%    |

## Best Performing Model

Logistic Regression achieved the highest performance with:

* Accuracy: 83.8%
* F1 Score: 0.845
* Strong generalization ability on unseen biomedical abstracts

---

# Evaluation Metrics

The models were evaluated using:

* Accuracy (CA)
* Precision
* Recall
* F1 Score
* AUC
* MCC
* Specificity
* Log Loss

5-fold cross-validation ensured reliable performance estimation.

---

# Key Findings

* Logistic Regression performed best for PCA-reduced TF–IDF features.
* COVID-19 abstracts showed the strongest semantic cohesion.
* Naive Bayes struggled because of feature independence assumptions.
* Neural Network captured complex nonlinear relationships effectively.
* The workflow generalized well on unseen biomedical abstracts.


---

# Applications

* Biomedical literature classification
* Scientific paper categorization
* NLP-based biomedical research
* Knowledge discovery from literature
* Bioinformatics text analytics
* Automated literature mining

---

# Future Scope

* Integration with BioBERT and transformer models
* Named Entity Recognition (NER)
* Large-scale PubMed analysis
* Real-time biomedical literature classification
* Deployment as a web-based research assistant

---

# Author

Anjali saini
M.Sc. Bioinformatics
Maharshi Dayanand University, Rohtak

