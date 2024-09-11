# Sentiment-Analysis-for-Employee-Satisfaction-during-COVID-19-Pandemic

This project performs sentiment analysis on employee reviews from Glassdoor during the COVID-19 pandemic, focusing on major Silicon Valley companies such as Apple, Facebook, and Google. The aim is to assess employee satisfaction during this period by analyzing review sentiments, with potential insights for investors and business analysts **because** during the COVID-19 pandemic, companies adopted various strategies to manage operations and employee well-being. This project seeks to analyze employee reviews, focusing on their pros and cons, to gauge overall satisfaction across different companies. By applying sentiment analysis to these reviews, we can derive valuable insights about how employees perceived their employers' responses during the pandemic.

## Datasets Used
1. **data_glassdoor_hw1.csv**: Contains employee reviews for major tech companies.
2. **positive.txt**: A list of positive sentiment words.
3. **negative.txt**: A list of negative sentiment words.
4. **stopwords.txt**: A list of common stopwords to exclude during text analysis.

## Key Steps

### 1. Data Preprocessing
- The Glassdoor dataset is loaded, and reviews from Apple, Facebook, and Google are extracted.
- Pros and cons of each company are separated for sentiment analysis.
- Stopwords, positive, and negative word lists are imported to assist in the sentiment scoring.

### 2. Sentiment Analysis
- Sentiment scores are calculated based on the presence of positive and negative words in the reviews.
- Reviews are categorized into **positive**, **negative**, or **neutral** based on the calculated sentiment score.
- The project analyzes both the pros and cons of employee feedback to get a holistic understanding of satisfaction levels.

### 3. Company Comparison
- Sentiment scores for each company (Apple, Facebook, Google) are compared, allowing for a detailed assessment of which companies had more positive or negative employee experiences during the pandemic.

## Technologies Used
- **Languages**: Python
- **Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - Custom Python functions for sentiment scoring based on word lists.

## Key Insights
- Employee satisfaction varied significantly across companies during the pandemic.
- Sentiment analysis revealed the differences in how companies like Apple, Facebook, and Google handled the challenges posed by COVID-19.
- The **pros** section of reviews tended to have more positive sentiment, while **cons** highlighted specific concerns employees faced.

## Limitations
- The analysis is based solely on sentiment words, which may not fully capture nuanced opinions.
- The dataset only includes reviews from major Silicon Valley companies, which might limit broader generalizations.

## Future Enhancements
- Expand the dataset to include more companies or other industries.
- Incorporate advanced NLP techniques, such as machine learning models or deep learning-based sentiment analysis, for better accuracy.
