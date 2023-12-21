**Sentiment Analysis in Python**

This Python notebook demonstrates sentiment analysis using two different techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner) and a pre-trained Roberta model from Hugging Face.

**Technologies used**

- Python: The primary programming language used for writing the code.

- Pandas: A powerful data manipulation library used for reading, analyzing, and manipulating tabular data.

- NumPy: A library for numerical operations in Python, often used for handling numerical arrays and computations.

- Matplotlib: A popular plotting library for creating static, interactive, and animated visualizations in Python.

- Seaborn: A data visualization library based on Matplotlib that provides a high-level interface for drawing attractive statistical graphics.

- NLTK (Natural Language Toolkit): A library for working with human language data. In this code, NLTK is used for basic natural language processing tasks such as tokenization and part-of-speech tagging.

- TQDM: A library for creating progress bars in the command line interface, used here to visualize progress during iterations.

- Transformers (Hugging Face): A library by Hugging Face for working with state-of-the-art natural language processing models, including pre-trained models like Roberta.

- scipy: A library used here for the softmax function, which is employed to normalize the output scores from the Roberta model.

- Transformers Pipeline: From Hugging Face's Transformers library, used for easily running sentiment predictions with pre-trained models.

**Steps Covered:**

**Data Loading and EDA:**

Read in the dataset and perform a quick exploratory data analysis.

**VADER Sentiment Scoring:**

- Utilize NLTK's SentimentIntensityAnalyzer to get the neg/neu/pos scores of the text using a "bag of words" approach.
- Visualize the compound score distribution for different Amazon star reviews.

**Roberta Pretrained Model:**

- Use a pre-trained Roberta model from Hugging Face for sentiment analysis.
- Compare the results with VADER scores

**Combine and Compare:**

- Combine results from VADER and Roberta.
- Visualize and compare sentiment scores between models.

**Review Examples:**

Explore examples where model scoring and review scores differ the most, including positive 1-star and negative 5-star reviews.

**Extra: Transformers Pipeline:**

Showcase the Transformers Pipeline for quick and easy sentiment predictions.

