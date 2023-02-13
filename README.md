# World's history through analysis of newspapers' headlines. 
Scraping the headlines of the newspapers and training the neural network to create new headlines based on the old ones.

___

## The outline of the project:
0. Review of the methods
1. Choosing the methods of the study
2. Scraping the data
3. Profiling and cleaning the data
4. Exploration and vizualization of the data
5. Preprocessing the data
6. NLP analys \
  6a.  
  6b. Sentiment analysis   
  6c. Tokenization and vectorization of thr data       
  6d.      
7. Choosing the Text generating model  
8. Training of the NN  
9. Deploying the model. Results

___

## Choosing the subjects and methods of the study

~~This was mistaken text~~

### Python libraries that are useful for the project

| Library | What for | Analysis part|
| :---- | :----: | ----: |
| **os**| for handling files | R1C3 |
| **numpy**| to work with multi-dimensional arrays and matrices | R2C3 |
| **pandas**| to work with data to analyze it | R2C3 |
| **textblob**| to process textual data for NLP | R2C3 |
| **matplotlib.pyplot**| allows to visualize data in multiple ways | R2C3 |
| **re**| to check if a specified string and a given regular expression match | R2C3 |
| **wordcloud**| to generate a word cloud in Python for visualization| R2C3 |
| **better_profanity**| to censor data | R2C3 |
| **pillow**| library is a package that enables image reading. Pillow is a wrapper for PIL - Python Imaging Library | R2C3 |
| **markovify**| to generate headlines | simple, extensible Markov chain generator |
| **os**| for handling files | R1C3 |
| **-**| R2C2 | R2C3 |


## Scraping the data

[Web scraping with Python](https://iqss.github.io/dss-workshops/PythonWebScrape.html)

Different methods 

### BeautifulSoup

[Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)

[A short & practical HOW-TO guide to scrape data from a website using Python](https://towardsdatascience.com/a-short-practical-how-to-guide-to-scrape-data-from-a-website-using-python-888373227d4f)

[How To Scrape Web Pages with Beautiful Soup and Python 3](https://www.digitalocean.com/community/tutorials/how-to-scrape-web-pages-with-beautiful-soup-and-python-3)

[Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)

[The Art of Web Scraping](https://betterprogramming.pub/the-art-of-web-scraping-382e2ea43c18) - example with ebay


[Web Scraping news articles in Python](https://towardsdatascience.com/web-scraping-news-articles-in-python-9dd605799558) - wep-page design and BeautifulSoup

### Selenium

Selenium is a powerful tool for advanced interactions with websites: login, clicks and etc.

[Mastering the art of web scraping with Selenium and Python](https://towardsdatascience.com/mastering-the-art-of-web-scraping-with-selenium-and-python-part-2-2-66ee4f3b5f44)

[Mastering the art of web scraping with Selenium and Python [Part 2/2]
](https://towardsdatascience.com/mastering-the-art-of-web-scraping-with-selenium-and-python-part-2-2-66ee4f3b5f44) - collect all the artists available on Spotify. 

### Scrapy

[Using Scrapy to Build your Own Dataset](https://towardsdatascience.com/using-scrapy-to-build-your-own-dataset-64ea2d7d4673)

[How to Scrape The New York Times using Python Scrapy](https://proxiesapi-com.medium.com/how-to-scrape-the-new-york-times-using-python-scrapy-6b9a90d4a575) - also using BeautifulSoup to scrape New York Times articles

#### New York Times data scraping

[pynytimes - Use most New York Times APIs, get all the data you need from the Times!](https://github.com/michadenheijer/pynytimes)
##### New York Times official API

I would like to thank Brienna Herold for her article about [How to Collect Data From The New York Times Over Any Period of Time](https://towardsdatascience.com/collecting-data-from-the-new-york-times-over-any-period-of-time-3e365504004)

[Link to New York Time developer's page](https://developer.nytimes.com)

[Link to New York Time official API](https://developer.nytimes.com/apis)

[New York Times archive](https://developer.nytimes.com/docs/archive-product/1/overview)

[Using New York Times API and jq to collect news data](https://medium.com/@danalindquist/using-new-york-times-api-and-jq-to-collect-news-data-a5f386c7237b)

[Web Scraping The New York Times Articles with Python : Part I](https://medium.com/codex/web-scraping-the-new-york-times-articles-with-python-part-i-e2d6fc02d4e0) - scraping with API

##### New York Times data scraping with Scrapy

[How to Scrape The New York Times using Python Scrapy](https://www.proxiesapi.com/blog/how-to-scrape-the-new-york-times-using-python-scra.html.php)




[How to Scrape The New York Times using Python Scrapy](https://proxiesapi-com.medium.com/how-to-scrape-the-new-york-times-using-python-scrapy-6b9a90d4a575)

[Tutorial](https://www.youtube.com/watch?v=v_r0nO_ocVg)

### Washington Times data scraping 

[Scraping Articles from the Washington Post](https://lingfeiwu1.gitbooks.io/data-mining-in-social-science/content/scraping_articles_from_the_washington_post/) - short example with BeautifulSoup
[Scraping Washington Post with Python and Beautiful Soup](https://proxiesapi.com/blog/scraping-washington-post-with-python-and-beautiful.html.php)

## Profiling and cleaning the data

## Exploration and vizualization of the data


## Preprocessing the data

[Language Processing Pipelines](https://spacy.io/usage/processing-pipelines)

[Analyzing The New York Times Articles with Python: Part II — Text Data Preprocessing: A Step-by-Step Guide](https://medium.com/codex/analyzing-the-new-york-times-articles-with-python-part-ii-text-data-preprocessing-a-1cf7425acb86) - tokenization, removing punctuation and stop words, lemmatization and collocations.
In the part 3 - topic discovery using LDA and sentiment analysis using TextBlob

## NLP

[Spacy library](https://spacy.io)
[Natural Language Processing With spaCy in Python](https://realpython.com/natural-language-processing-spacy-python/#visualization-using-displacy)

[Using neural networks to analyze mainstream and sensational news headlines](https://github.com/marshuang80/Headline_neural_networks) - 
"headline_prediction.py" trains a CNN that predicts if a news headline is being labled as "real"or "fake". The script will generate a graph of training and validation accuracy for each epoche.



[Automatically generate headlines to short articles](https://github.com/udibr/headlines)

### Sentiment analysis

[Topic Modelling using LDA and LSA in Sklearn](https://www.kaggle.com/code/rajmehra03/topic-modelling-using-lda-and-lsa-in-sklearn)

[Topic Modelling with LSA and LDA](https://www.kaggle.com/code/rcushen/topic-modelling-with-lsa-and-lda)

[K-means Clustering of 1 million headlines](https://www.kaggle.com/code/thebrownviking20/k-means-clustering-of-1-million-headlines/notebook)

[Meaningful Random Headlines by Markov Chain](https://www.kaggle.com/code/nulldata/meaningful-random-headlines-by-markov-chain)

[News_articles_classif (Wordembeddings&RNN)](https://www.kaggle.com/code/avikumart/nlp-news-articles-classif-wordembeddings-rnn/notebook#1.-Data-exploration-and-pre-processing)

[Recommending news articles based on read articles](https://www.kaggle.com/code/vikashrajluhaniwal/recommending-news-articles-based-on-read-articles)

[News Category Classifier](https://www.kaggle.com/code/hengzheng/news-category-classifier-val-acc-0-65)
[Creating Twitter Sentiment Analyzer using Python to gather insights on Stocks](https://tradewithpython.com/sentiment-analysis-for-stocks-from-twitter)

[Creating Your Own Recent Stock News Sentiment Analyzer using Python](https://tradewithpython.com/news-sentiment-analysis-using-python)

[Twitter example of Sentiment analysis](https://medium.com/@nikitasilaparasetty/twitter-sentiment-analysis-for-data-science-using-python-in-2022-6d5e43f6fa6e)

[Twitter Sentiment Analysis for Data Science Using Python in 2022](https://medium.com/@nikitasilaparasetty/twitter-sentiment-analysis-for-data-science-using-python-in-2022-6d5e43f6fa6e)

[R: Scraping The New York Times For Sentiment Analysis Of Presidential Candidates](https://rstudio-pubs-static.s3.amazonaws.com/503266_3d55c43b76614a8da0a935c60016cd02.html) - in R, not python, but interesting ideas about the analysis itself

## Choosing the Text generating model

### Generating text with Markov Chains 

[Coronavirus-news-analysis by Brienna](https://github.com/brienna/coronavirus-news-analysis/blob/master/2020_05_06_markovify.ipynb)

[Simulating Text With Markov Chains in Python](https://towardsdatascience.com/simulating-text-with-markov-chains-in-python-1a27e6d13fc6) - generating Donald Trump speeches

[Simulating text with Markov chain in Python](https://towardsdatascience.com/simulating-text-with-markov-chains-in-python-1a27e6d13fc6)

[NLG for Fun — Automated Headlines Generator](https://towardsdatascience.com/nlg-for-fun-automated-headlines-generator-6d0459f9588f) - very basic usage of Markovify

[Text Generation with Markov Chains: An Introduction to using Markovify](https://towardsdatascience.com/text-generation-with-markov-chains-an-introduction-to-using-markovify-742e6680dc33) - Generating Text in Shakespearean English with Markov Chains

### Generating Text with Neural Networks

[Text generation with an RNN](https://www.tensorflow.org/text/tutorials/text_generation) - the notebook  to generate text using a character-based RNN

[Natural language generation](https://towardsdatascience.com/nlg-for-fun-automated-headlines-generator-6d0459f9588f)

[Generating Fake but Realistic Headlines Using Deep Neural Networks](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7121779/) - RNN, evaluation metrics description

[Generating News Headlines with Recurrent Neural Networks](https://nlp.stanford.edu/courses/cs224n/2015/reports/1.pdf) - some math and explanation behind RNN. Interesting examples of errors.

[Creating News Headlines with AI](https://andreasstckl.medium.com/creating-news-headlines-with-ai-2d8c5bb76241) - Tensorflow, Keras. “Characterlevel-RNN”

[A simple News Article Generator](https://medium.datadriveninvestor.com/a-simple-news-article-generator-6c3737359d09) - words-based generater. Training is done with a jupyter notebook on [AWS SageMaker](https://aws.amazon.com/de/sagemaker/)

[Character-Level Language Model](https://towardsdatascience.com/character-level-language-model-1439f5dd87fe)

[Yet another text generation project](https://towardsdatascience.com/yet-another-text-generation-project-5cfb59b26255) - Recurrent Neural Networks

[Headline Generation using Deep Neural Networks](https://scholarworks.sjsu.edu/cgi/viewcontent.cgi?article=1526&context=etd_projects) - RNN, LSTM, GRU

[Text classification](https://developers.google.com/machine-learning/guides/text-classification/step-1)

[Generating News Headlines with Machine Learning](https://medium.com/m2mtechconnect/generating-news-headlines-with-machine-learning-1a4f5b393eee) - using  textgenrnn, a neural network architecture that allows you to easily train a text-generating neural network of any size and complexity on any text dataset.

[Detecting Headline Sarcasm with Machine Learning](https://medium.com/m2mtechconnect/detecting-headline-sarcasm-with-machine-learning-4c3523104cdf)
The sarcastic news headlines are from The Onion, while nonsarcastic ones are from HuffPost. - the data set with kaggle

[Generating fake news](https://habr.com/ru/post/345190/) - comparison text generation Char-RNN vs Word Embeddings 

## Machine learning on large data set
[Using an Out-of-Core Approach to Process Large Datasets](https://towardsdatascience.com/how-to-speed-up-data-processing-in-pandas-a272d3485b24) - about vaex library

## One more analysis <sub>for the future</sub>

Alexander Baturo, Niheer Dasandi, and Slava Mikhaylov, "Understanding State Preferences With Text As Data: Introducing the UN General Debate Corpus" Research & Politics, 2017. doi: 2053168017712821
[DataSet of UN speaches](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0TJX8Y)

[Information extraction](https://www.analyticsvidhya.com/blog/2020/06/nlp-project-information-extraction/)

[SwiftKey's latest keyboard is powered by a neural network - about the first neural network keyboard](https://www.engadget.com/2015-10-08-swiftkey-neural-alpha.html)
[Example of headlines generator](http://www.upworthygenerator.com) - generator of funny headlines
[The website news generator](http://clickotron.com)
[Another fun example of generating headlines](https://vc.ru/services/238757-neyronnaya-set-generiruet-zagolovki-statey-dlya-vc-ru)

## Some interesting datasets

[News Category Dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset/code?datasetId=32526&sortBy=voteCount)
