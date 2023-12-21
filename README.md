**Sentiment Analysis in Python**

This Python notebook demonstrates sentiment analysis using two different techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner) and a pre-trained Roberta model from Hugging Face.

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

