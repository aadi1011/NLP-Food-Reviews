# Applying Natural Language Processing on Food Reviews Dataset Processing and ML Classification

In this project, we perform text preprocessing and use various vectorization techniques and machine learning algorithms to classify Amazon Fine Food Reviews. Below is a summary of the steps taken and the results obtained.

### Step 1: Data Download
The dataset used for this project is the [Amazon Fine Food Reviews dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) sourced from Kaggle.

### Step 2: Text Preprocessing
We performed the following text preprocessing steps using the NLTK and SpaCy libraries:

a) **Tokenization and Lemmatization**: We split the reviews into individual words (tokens) and converted them to their base or dictionary forms (lemmas) to standardize the vocabulary.

b) **Data Cleansing**: We removed stopwords, symbols, and URLs from the text data to eliminate noise and improve model performance.

### Step 3: Vectorization
We used different vectorization techniques to convert the preprocessed text data into numerical features:

a) **CountVectorizer**: This technique counts the frequency of each word in the text corpus, creating a matrix of word counts.

b) **TFIDFVectorizer (Term Frequency-Inverse Document Frequency)**: This technique assigns weights to words based on their importance in a document relative to the entire corpus.

c) **Word2Vec**: We used Word2Vec to create dense word embeddings based on the context of words in the corpus.

d) **GoogleNews Word2Vec**: This is a pre-trained Word2Vec model trained on a large Google News dataset.


