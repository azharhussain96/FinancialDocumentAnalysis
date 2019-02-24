# FinancialDocumentAnalysis
Based on Quantopian code of Lucy Wu

Built by Azhar Hussain and Elliot Adams

Python program that accepts tickers, scrapes 10K and Q's for the respective companies, and conducts various metrics of sentiment analysis. 

* Cosine and Jaccard similarity scores
  * Based on change in overall word count
* Word Count
  * Total change in word count
* Frequency of words based on the following sentiment lists
  * Negativity
  * Uncertainty
  * Litigiousness
  * Custom 500 word list
  * Below median frequent words
  * Above median frequent words
  * Quartile 1 frequent words
  * Quartile 4 frequent words
* Sentiment of new words added
* Total unique words added and removed
