# Hate-Speech-Detection-Using-DeepLearning
## Hate Speech Detection Using Deep Learning
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

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/b6f54413121322097441751e5a87a7b19b21752a/i2.png)

### EDA - Visualize class distribution using pie charts

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/b6f54413121322097441751e5a87a7b19b21752a/i3.png)

### EDA - Balanced Class Distribution

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/015e698597e2b462a7b5399e88e12acfef9f2821/i4.png)

### Text Preprocessing
* Convert to lowercase

* Remove punctuations

* Remove stopwords

* Lemmatization

![](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/9f33b58a74b3f1d299d8ac8266db578a663b5e4c/i5.png)

### Word Cloud Visualization

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/88d96a447a8f9e6f65680040e7a70e2a4ae806fd/i6.png)

### Building the Deep Learning Model
A hybrid model using:
* Embedding layer

* Bidirectional LSTM

* Dense layers with L1 regularization

* Batch Normalization

* Dropout

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/26f45c20debc3b190f1f43c49bfabf85cf791e0d/i7.png)

### Training the Model
Using:
* EarlyStopping

* ReduceLROnPlateau
Training for up to 50 epochs.

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/21b1f2825a578678f13175573d2ef95f06dc2c73/i8.png)

### Evaluating the Model

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/a960488b803b0e9684e42ef807eb0aa3eeae497d/i9.png)

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/6e2aa3a411788f62b2505ee705922852fd03882b/i10.png)

### Test Accuracy

![img](https://github.com/Ruchika-Natiye/Hate-Speech-Detection-Using-DeepLearning/blob/1a73b036dbbcafa8ccc671520acd2fe96f090f36/i11.png)

## 🔮 Future Improvements
* Upgrade model to BERT / DistilBERT

* Deploy with Flask/FastAPI

* web UI for real-time classification

* Improve dataset balancing with SMOTE / augmentation

## 👩‍💻 Author
Ruchika Natiye

Deep Learning | NLP | Hate Speech Detection
