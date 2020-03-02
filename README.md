# sentiment-analysis
The goal of this assignment is to use sentiment analysis to gain insights from a text dataset.
Input Data - The input dataset is a sample of fashion reviews crawled from Vogue during Fashion Week. The main content is the review text. The file also contains structured data (meta-data) such as “year”, “season”, “brand”, “author of review.”
Your objective is to analyze this dataset to understand fashion trends using sentiment analysis.
Tasks:
1. Open the file "fashion.csv" using pandas.
2. Generate polarity scores - positive, negative, neutral - for each review using NLTK*.
3. Save the output as "sentiment_output.csv". It should contain four columns:
1. ID, 2. Positive, 3. Negative, and 4. Neutral scores
4. Merge the output file with the original input file.
5. Summarize the sentiment scores for each of the four cities – New York, Paris, Milan, and London.
