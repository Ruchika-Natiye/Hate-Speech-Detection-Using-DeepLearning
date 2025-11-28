# Hate-Speech-Detection-Using-DeepLearning
# Hate Speech Detection Using Deep Learning
A deep learning–based text classification model that identifies whether a tweet is Hate Speech, Offensive Language, or Neutral.This project uses preprocessing, word embeddings, and a Bidirectional LSTM neural network.

## ✨ Overview
This project builds a text classification model capable of detecting hate speech from social media content.
It includes:
* Data loading and exploration

* Balancing imbalanced dataset

* Text preprocessing (cleaning, lemmatization, stopword removal)

* Tokenization & padding

* Deep learning model using Embedding + BiLSTM + Dense layers

* Training with early stopping and learning rate reduction

* Performance visualization

## 📂 Dataset
| Class | Meaning            |
| ----- | ------------------ |
| **0** | Hate Speech        |
| **1** | Offensive Language |
| **2** | Neutral            |

## 🧹 Text Preprocessing
Each tweet undergoes:
* Lowercasing

* Removal of punctuation

* Removal of stopwords

* Lemmatization using WordNet

* Tokenization

* Sequence padding
This ensures the text is clean and uniform before model training.

## 🎨 Word Cloud Visualization
A Word Cloud is generated to understand frequently appearing terms in the dataset (e.g., Neutral class).

## Steps Performed
### Importing Required Libraries

### Loading the Dataset

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/b35052f5ee39d99feabed4f174eb43039dec5b4c/i1.png)

### Dataset shape & Info

![img]()

### EDA - Visualize class distribution using pie charts

![img]()

### EDA - Balanced Class Distribution

![img]()

### Text Preprocessing
* Convert to lowercase

* Remove punctuations

* Remove stopwords

* Lemmatization

### Word Cloud Visualization

![img]()

### Building the Deep Learning Model
A hybrid model using:
* Embedding layer

* Bidirectional LSTM

* Dense layers with L1 regularization

* Batch Normalization

* Dropout

![img]()

### Training the Model
Using:
* EarlyStopping

* ReduceLROnPlateau
Training for up to 50 epochs.

![img]()

### Evaluating the Model

![img]()

![img]()

### Test Accuracy

![img]()
## 🔮 Future Improvements
* Upgrade model to BERT / DistilBERT

* Deploy with Flask/FastAPI

* web UI for real-time classification

* Improve dataset balancing with SMOTE / augmentation

## 👩‍💻 Author
Ruchika Natiye
Deep Learning | NLP | Hate Speech Detection
