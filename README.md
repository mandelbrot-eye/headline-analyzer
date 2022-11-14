# World's history through analysis of newspapers' headlines.
Scraping the headlines of the newspapers and training the neuronal network to create new headlines based on the old ones.
___

## The outline of the project:
1. Choosing the subjects and methods of the study
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

### Choosing the subjects and methods of the study

#### Python libraries that are useful for the project

**os**: for handling files\ 
**numpy**: to work with multi-dimensional arrays and matrices.  \
**pandas**: used to work with data to analyze it.  \
**textblob**: to process textual data for NLP.  \
**matplotlib.pyplot**:  allows to visualize data in multiple ways.  \ 
**re**: to check if a specified string and a given regular expression match.  \
**wordcloud**: to generate a word cloud in Python for visualization.  \
**better_profanity**: to censor data. \ 
**pillow**: library is a package that enables image reading. Pillow is a wrapper for PIL - Python Imaging Library.
~~This was mistaken text~~
<sub>This is a subscript text</sub>

`rgb(9, 105, 218)`
`#0969DA`


| Header1 | Header2 | Header3 | 
| :---- | :----: | ----: |
| R1C1 | R1C2 | R1C3 |
| R2C1 | R2C2 | R2C3 |

### Scraping the data

[Web scraping with Python](https://iqss.github.io/dss-workshops/PythonWebScrape.html)

[Mastering the art of web scraping with Selenium and Python](https://towardsdatascience.com/mastering-the-art-of-web-scraping-with-selenium-and-python-part-2-2-66ee4f3b5f44)

[Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)

[Web Scraping news articles in Python](https://towardsdatascience.com/web-scraping-news-articles-in-python-9dd605799558)

[Using Scrapy to Build your Own Dataset](https://towardsdatascience.com/using-scrapy-to-build-your-own-dataset-64ea2d7d4673)

[How To Scrape Web Pages with Beautiful Soup and Python 3](https://www.digitalocean.com/community/tutorials/how-to-scrape-web-pages-with-beautiful-soup-and-python-3)

[The Art of Web Scraping](https://betterprogramming.pub/the-art-of-web-scraping-382e2ea43c18)

[A short & practical HOW-TO guide to scrape data from a website using Python](https://towardsdatascience.com/a-short-practical-how-to-guide-to-scrape-data-from-a-website-using-python-888373227d4f)

#### New York Times data scraping
##### New York Times official API

I would like to thank Brienna Herold for her article about [How to Collect Data From The New York Times Over Any Period of Time](https://towardsdatascience.com/collecting-data-from-the-new-york-times-over-any-period-of-time-3e365504004)

[Link to New York Time official API](https://developer.nytimes.com/apis)

##### New York Times data scraping with Spacy

[How to Scrape The New York Times using Python Scrapy](https://www.proxiesapi.com/blog/how-to-scrape-the-new-york-times-using-python-scra.html.php)

[Web Scraping The New York Times Articles with Python : Part I](https://medium.com/codex/web-scraping-the-new-york-times-articles-with-python-part-i-e2d6fc02d4e0)

[How to Scrape The New York Times using Python Scrapy](https://proxiesapi-com.medium.com/how-to-scrape-the-new-york-times-using-python-scrapy-6b9a90d4a575)

[Tutorial](https://www.youtube.com/watch?v=v_r0nO_ocVg)

#### Washington Times data scraping 

[Link](https://lingfeiwu1.gitbooks.io/data-mining-in-social-science/content/scraping_articles_from_the_washington_post/)
[Scraping Washington Post with Python and Beautiful Soup](https://proxiesapi.com/blog/scraping-washington-post-with-python-and-beautiful.html.php)

### Profiling and cleaning the data

### Exploration and vizualization of the data


### Preprocessing the data

### NLP

[Spacy library](https://spacy.io)
[Natural Language Processing With spaCy in Python](https://realpython.com/natural-language-processing-spacy-python/#visualization-using-displacy)

####
#### Sentiment analysis

[Twitter example of Sentiment analysis](https://medium.com/@nikitasilaparasetty/twitter-sentiment-analysis-for-data-science-using-python-in-2022-6d5e43f6fa6e)

[R: Scraping The New York Times For Sentiment Analysis Of Presidential Candidates](https://rstudio-pubs-static.s3.amazonaws.com/503266_3d55c43b76614a8da0a935c60016cd02.html)

### Choosing the Text generating model
[Generating Fake but Realistic Headlines Using Deep Neural Networks](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7121779/)

[Simulating text with Markov chain in Python](https://towardsdatascience.com/simulating-text-with-markov-chains-in-python-1a27e6d13fc6)

[Natural language generation](https://towardsdatascience.com/nlg-for-fun-automated-headlines-generator-6d0459f9588f)

[Generating News Headlines with Recurrent Neural Networks](https://nlp.stanford.edu/courses/cs224n/2015/reports/1.pdf)

[Creating News Headlines with AI](https://andreasstckl.medium.com/creating-news-headlines-with-ai-2d8c5bb76241)

[Yet another text generation project](https://towardsdatascience.com/yet-another-text-generation-project-5cfb59b26255)

[Headline Generation using Deep Neural Networks](https://scholarworks.sjsu.edu/cgi/viewcontent.cgi?article=1526&context=etd_projects)

[Text classification](https://developers.google.com/machine-learning/guides/text-classification/step-1)

[Generating News Headlines with Machine Learning](https://medium.com/m2mtechconnect/generating-news-headlines-with-machine-learning-1a4f5b393eee)

[Detecting Headline Sarcasm with Machine Learning](https://medium.com/m2mtechconnect/detecting-headline-sarcasm-with-machine-learning-4c3523104cdf)

## One more analysis

Alexander Baturo, Niheer Dasandi, and Slava Mikhaylov, "Understanding State Preferences With Text As Data: Introducing the UN General Debate Corpus" Research & Politics, 2017. doi: 2053168017712821
[DataSet of UN speaches](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0TJX8Y)

[Information extraction](https://www.analyticsvidhya.com/blog/2020/06/nlp-project-information-extraction/)
