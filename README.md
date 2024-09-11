### Company Analysis: Named Entity Recognition and Topic Modeling

This project is part of the UChicago Applied Data Science program and involves analyzing a collection of tweets and news articles about a specific company. The project consists of two parts: named entity recognition (NER) and topic modeling.

<br>
<br>
<br>

**Part A: Named Entity Recognition (NER) for Company and Location Identification**

The goal of this part is to identify the main company being discussed, other frequently mentioned companies, and locations related to the company.

**Approach:**
* **NER Analysis:** Extract entities (such as companies and locations) from the text using NER techniques.
* **Text Cleaning:** Apply methods to clean the data and discard non-English results.
* **Separate Entities:** Analyze entities from titles and texts separately in news articles.
* **Company & Location Identification:** Identify which companies and locations are frequently mentioned alongside the primary company.
* **Comparison of NER Models:** Use multiple NER tools (like NLTK and SpaCy) and compare their performance.

**Output:**
* **Top-20 Companies:** A list of the top-20 companies sorted by frequency, displayed in tables.
* **Most Frequent Locations:** Analysis of the most mentioned locations related to events.
<br>
<br>
<br>

**Part B: Topic Modeling for Important Topics Identification**

In this part, topic modeling is used to identify the top N most important topics from tweets and news articles about the company.

**Approach:**
* **Text Cleaning:** Clean the tweets and articles to remove noise and prepare for topic modeling.
* **Topic Modeling:** Apply topic modeling techniques (such as LDA) to identify key topics.
* **Title and Text Combination:** Combine the information from both the title and text of news articles to improve topic detection.
* **Selection of N:** Carefully choose the number of topics (N) to minimize duplication and maximize relevance.

**Output:**
* **Top N Topics:** A list of the most important topics from the tweets and articles, visualized and explained.
* **Topic Distribution:** Analysis of how topics are distributed across tweets and news articles.

<br>
<br>
<br>

**Conclusion**

This project explores the application of NER for company and location identification, as well as topic modeling for extracting key topics from a large dataset of tweets and news articles.

<br>
<br>
<br>

**How to Use**

Run the provided Jupyter Notebooks (Company Analysis_Starter1.ipynb for Part A and Company Analysis_Starter2.ipynb for Part B) to reproduce the results and visualizations.


