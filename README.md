If GitHub is unable to render a Jupyter notebook, copy the link of the notebook and enter it into the nbviewer: https://nbviewer.jupyter.org/


# NLP with Bag of Words (BoW)

This repository contains a collection of three Jupyter notebooks that explore key aspects of Natural Language Processing (NLP) using the Bag of Words (BoW) model and related techniques. Each notebook serves as a comprehensive guide, covering distinct but interconnected topics in the NLP workflow.

### 1. **NLP-1: Feature Extraction using the BoW Model**
In this notebook, we focus on the foundational step of feature extraction, which is crucial for preparing text data for analysis. The feature extraction process typically involves four key steps:
- **Text Standardization:** Utilizing techniques like stemming and lemmatization to normalize words.
- **Text Preprocessing:** Implementing methods such as tokenization and stop word removal to clean the text data.
- **Vocabulary Construction and Indexing:** Building a structured representation of the unique words in the dataset.
- **Vectorization of Features:** Converting the processed text into numerical format.

We specifically employ the Bag of Words (BoW) model for feature vectorization, which is a word order-agnostic approach, contrasting with sequence models that preserve word order.

### 2. **NLP-2: Text Visualization**
This notebook focuses on visualizing text data. We first create word vectors using Word2Vec and document vectors with Doc2Vec, followed by dimensionality reduction techniques such as PCA and t-SNE. Finally, we visualize the transformed vectors and explore the data using Word Clouds to provide intuitive insights into the textual information.

### 3. **NLP-3: Text Classification Using the BoW Model**
In our final notebook, we apply the BoW model to classify text data effectively. We implement a text classification pipeline that includes model selection, training, and evaluation, emphasizing practical applications of the techniques discussed in the previous notebooks.

By working through these notebooks, users will gain a solid understanding of key NLP concepts and techniques, specifically focusing on the Bag of Words model and its applications in feature extraction, visualization, and classification.
