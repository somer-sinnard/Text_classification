The Python code used to complete the project is found in this repository. A brief summary of each file is provided below:

1_articleScraping.ipynb
  - 8,765 articles from medscape.com were scraped and saved into individual HTML files and all relevant content was written and saved into a CSV file
  - Python packages utilized here were: Requests, BeautifulSoup, Pandas, os, and time

2_classificationSampling.ipynb
  - The extracted text was tokenized and a sample of 2,000 highly subjective sentences with were saved and exported for manual classification performed by our team
  - Sentences were labeled either as 1: positive sentiment, 0: neutral sentiment, or -1: negative sentiment
  - Python packages utilized here were: Pandas, NLTK, and TextBlob

3_All Classification Models.ipynb
  - Eight machine learning algorithms were applied to our manually classified sentences and optimized to yield the highest accuracy possible
  - Our best model was chosen and applied to new data to evaluate its performance
  - The following algorithms were applied to the data:
    - k-Nearest Neighbors
    - Logistic Regression
    - Multinomial Naive Bayes
    - Decision Trees
    - Random Forest
    - Linear Support Vector Machines
    - Kernelized Support Vector Machines
    - Neural Networks
  - Python packages utilized here were: Pandas, sci-kit learn

4_GensimLDA.ipynb
  - The text from all scraped articles was tokenized and used to conduct topic modeling which was also visualized in an interactive plot
  - Python packages utilized here were: Pandas, NLTK, Gensim, pyLDAvis, Matplotlib

5_Kmeans.ipynb
  - K-Means clustering was utilized as another method of topic modeling and 22 clusters/topics were extracted and visualized in an interactive plot
  - Python packages utilized here were: Pandas, sci-kit learn, NLTK, Collections, pyLDAvis
