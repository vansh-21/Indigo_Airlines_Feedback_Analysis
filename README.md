✈️ IndiGo Airlines Feedback Analysis

This project focuses on analyzing customer feedback data for IndiGo Airlines to identify common themes, satisfaction levels, and improvement areas.
The analysis was performed entirely in Google Colab using Python.

📘 Project Overview

Airline companies receive large volumes of passenger feedback daily.
Understanding this data manually is time-consuming and error-prone.

This project automates the process — reading, cleaning, and analyzing textual feedback to generate a summary of what customers think about the airline’s services.

🧠 Objectives

Process and clean raw customer feedback

Detect positive and negative expressions within reviews

Derive a summarized understanding of overall sentiment

Identify keywords related to praise or complaints

🛠️ Technologies Used

Python (Google Colab)

Pandas, NumPy – Data handling and preparation

TextBlob / NLTK – Text cleaning and sentiment analysis

Regular Expressions (re) – Text preprocessing

⚙️ Approach

Data Upload: Load raw feedback data into Colab

Text Cleaning: Remove punctuation, special characters, and convert to lowercase

Sentiment Processing: Analyze polarity and subjectivity using TextBlob or VADER

Keyword Identification: Extract frequent words and recurring feedback terms

Summary Generation: Aggregate findings into a concise textual summary

📈 Summary of Findings

From the processed feedback, customers frequently discussed:

Positive Aspects: Service quality, punctual flights, polite staff

Negative Aspects: Baggage handling delays, long check-in times, occasional flight delays

Overall, the sentiment leaned positive, with many passengers satisfied with the airline’s professionalism and service reliability.

💬 Conclusion

This project demonstrates how Python can be used to convert large volumes of unstructured customer text into actionable business insights.
It highlights the importance of sentiment-driven service improvement in the airline industry.
