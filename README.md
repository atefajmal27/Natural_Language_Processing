# Natural Language Processing
![](https://user-images.githubusercontent.com/62320593/95019859-ca2e5700-0635-11eb-9c94-f7d698385c64.jpeg)

## Background
There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

## My Solution
I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

### Steps to my solution:
### 1. Sentiment Analysis
Used the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.
<img width="541" alt="Screen Shot 2020-10-04 at 11 47 55 AM" src="https://user-images.githubusercontent.com/62320593/95020150-7d4b8000-0637-11eb-85d9-507f41b02216.png">

### 2. Natural Language Processing
In this section, I used NLTK and Python to tokenize the text for each coin. Then, I created a wordcloud to visualize the most occuring words.
<img width="1078" alt="Screen Shot 2020-10-04 at 11 52 22 AM" src="https://user-images.githubusercontent.com/62320593/95020261-18dcf080-0638-11eb-97a2-e437077d1d75.png">

