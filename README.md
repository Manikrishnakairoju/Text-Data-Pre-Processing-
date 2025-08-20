# Text-Data-Pre-Processing
Text Data Pre-Processing  Natural Language Processing (NLP) Used Constiution.csv file 

Tasks Performed:

Dataset Selection

Select a dataset that aligns with your interests and objectives for the text analysis. Consider the following criteria:
Ensure the dataset is relevant to your area of study or interest.
Choose a dataset that is readily accessible and publicly available, preferably in a format suitable for analysis (e.g., CSV, or Excel).
Consider the size of the dataset and whether it is manageable for your analysis purposes.
Assess the quality of the dataset in terms of completeness, accuracy and reliability.

Data Loading and Exploration 

Load any dataset for text analysis using Pandas.
Explore the dataset by examining its shape, data types and some descriptive statistics for the Text column (for example, length distribution).
Print a few sample rows.

Text Cleaning

Convert all text in the Text column to lowercase. Explain why this is important for text pre-processing.
Remove punctuation characters from the reviews. Consider using regular expressions or string manipulation techniques. Discuss the potential trade-offs of removing punctuation.
Remove common stop words (such as “the”, “a”, “is”, “of”) from the reviews. You can use the NLTK library or create a custom stop word list. Explain the rationale behind stop word removal.
Split the text into individual words (tokens). Discuss the role of tokenization in text processing.

Text Normalization
Apply either stemming or lemmatization to reduce words to their base form (such as  “running”  “run”, “better”  “good”). Choose the appropriate technique and explain its advantages and limitations.
Define a strategy for handling emojis and slang in the dataset. This could involve replacing them with descriptive words, creating a mapping dictionary, or ignoring them based on your analysis. Discuss the pros and cons of each approach.
Decide how to handle numbers in the reviews. Options include keeping them as-is, converting them to text (example: “five”) or removing them. Explain your reasoning.
