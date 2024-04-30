## TikTok App Reviews Analysis
### Overview
This project analyzes user reviews of the TikTok app to gain insights into user sentiments, trends, and feedback. By leveraging natural language processing (NLP) techniques and machine learning algorithms, we aim to understand what users appreciate about the app, identify common complaints, and provide recommendations for product development and customer satisfaction improvement.

### Data
Dataset link: [AppReviews Dataset](https://drive.google.com/file/d/1TCyun0B8C4j97jxCYIdQ76mTK0FX-vLo/view?usp=sharing)
The dataset used in this analysis consists of millions of user reviews collected from the TikTok app. Each review includes information such as the review text, number of upvotes, app version, and posted date. We perform data cleaning and preprocessing to handle missing values, remove noise, and prepare the text data for analysis.

### Analysis
### Data Cleaning and Preprocessing
- We handle missing values and duplicate rows, ensuring data integrity for analysis.
- Text data undergoes preprocessing steps such as lowercasing, removal of URLs and special characters, tokenization, stop word removal, and lemmatization to prepare it for analysis.

### Exploratory Data Analysis (EDA)
- We use VADER sentiment analysis to categorize reviews as positive, negative, or neutral based on sentiment scores.
- Sentiment trends over time are visualized to identify patterns in user sentiments.
- Word frequency analysis and word clouds are generated to understand common topics and themes in user reviews.

### Feature Extraction
- We employ BERT (Bidirectional Encoder Representations from Transformers) for feature extraction, extracting features from review text to understand deeper contextual information.
- Named Entity Recognition (NER) is used to identify and extract named entities such as organizations, persons, and locations from the text data.

### Topic Modeling
- Latent Dirichlet Allocation (LDA) is utilized to uncover latent topics within the review data, providing insights into common themes and discussions among users.

### Recommendations
Based on the analyses conducted, we provide recommendations for product development and customer satisfaction improvement, including:

- Enhancing music-related features and content.
- Prioritizing technical improvements to address reported issues.
- Implementing user feedback mechanisms to gather insights continuously.

### Conclusion
By implementing these recommendations, the TikTok app can enhance its offerings, address user concerns, and improve overall customer satisfaction, leading to increased user engagement and loyalty.


### Prerequisites
You need to have Python installed on your system along with the necessary libraries used in the project. You can install all required libraries using the following command:
```bash
pip install -r requirements.txt
```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/devanshijoshi08/TikokAppReview-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Open `TikTokAppReviews.ipynb` in Jupyter Notebook to view the analysis.
