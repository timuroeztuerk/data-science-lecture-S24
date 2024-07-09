# Data Science: S 2024 - Text as Data
Welcome to the course! This semester, we will focus on text analysis and how we can (1) think about, find, and use text as a data point, (2) use Python, NLTK, and SpaCy to create neat datasets, (3) and create projects which could be a springboard for a thesis in the future.

We will also talk about more advanced concepts like natural language processing (NLP), large language models (LLM), and the advancement of AI in the past couple of years. It won't necessarily be our sole focus, but it is probably one of the reasons you are attending this course. 

I organized the course around Google Colab (GC), requiring you to have a Google account. The main reason for using this platform is that it will improve accessibility and reduce the headache of understanding and building Python environments. This way, you will use and run all your code from any computer without having specific hardware or installing a specific software. Believe me, some students sometimes had this type of problem even a week before their submission dates!

https://research.google.com/colaboratory/faq.html#whats-colaboratory

Every week, you will find two GC notebooks; the first we will use during our course, and the second is a short, optional homework that will boost your understanding if you opt-in. Besides the notebooks, I will post links and resources that should advance you further in that specific topic, I highly recommend checking them out.

Note: The GitHub page is a bit different than the E-Learning page, as it is condensed to include only the teaching, not the application parts.

### Week 1
Welcome to Week 1. This week, we will talk about our course in general and start with the basics of Python, the programming language we will use throughout this course. An up-to-date syllabus and administrative and organizational information can be found here.

Here are some other resources that will be helpful to you:

[PyFlo](https://pyflo.net/): A beginner guide recommended by python.org. I recommend such resources more than video tutorials, as you are more inclined to revisit them and complete small projects.

[Getting Started with Pandas](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html): Pandas library will be our primary tool when dealing with data, which is also an industry standard. The guide on their website is quite welcoming.

[Pandas Compared to R](https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_r.html) \& [Pandas Compared to Stata](https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_stata.html): Most of you have already worked with R or Stata, so here are two links to make your life easier.

### Week 2

Welcome to Week 2! After learning the basics of Python and Pandas, we will start with the basic concepts of using text as data. This week, we will look at how the computer sees the text and how we can manipulate that using regular expressions.

Regular expressions will be the most fundamental tool in your toolkit, and lucky for you, there have been a lot of advancements in the field, now you can use it almost without memorizing syntax. Then, we will examine how words are tokenized, the essential transformation we do during natural language processing.

Lastly, I will give you an assignment, which is a task I did a couple of weeks ago for my own research. Hopefully, you will see how regular expressions and programming will be helpful to you.

Some resources that I've used for the lecture, and you should check out:

[DataCamp Cheat Sheet](https://www.datacamp.com/cheat-sheet/regular-expresso)
[RealPython Regex](https://realpython.com/regex-python/)
[Programiz](https://www.programiz.com/python-programming/regex)
[Geeksforgeeks](https://www.geeksforgeeks.org/regular-expression-python-examples/)
[Google](https://developers.google.com/edu/python/regular-expressions)
[Python Docs](https://docs.python.org/3/library/re.html)
[lukehaas.me](https://projects.lukehaas.me/regexhub/)
[Debuggex](https://www.debuggex.com/cheatsheet/regex/python)

### Week 3

Welcome to Week 3! We will pick up where we left off last week and go further into regular expressions, use cases, and tokenization, and finally have some real NLP experience with the infamous book of Adam Smith, The Wealth of Nations. Some concepts will be abstract for you, but you can think of weeks three and four as a unit. Next week, instead of learning new concepts, we will apply our knowledge so far in real-world applications.

Useful resources for this week:

[Neptune.ai](https://neptune.ai/blog/tokenization-in-nlp)
[SpaCy Documentation](https://spacy.io/usage/spacy-101): Have a look at the course "Advanced NLP with SpaCy".

### Week 4

Welcome to Week 4! Don't forget to have a look at the material from previous weeks. This week we will apply our knowledge and look at our first assignment (12.5\% of your overall grade).

Check out the following paper: 
Michalopoulos and Rauh. 2024. Movies. Cambridge Working Papers in Economics.

### Week 5

Welcome to Week 5! This week we will explore topic identification and classification. Check out the links I provided below, these Kaggle notebooks are really good examples of NLP projects.

[Kaggle - Topic Modelling](https://www.kaggle.com/code/arthurtok/spooky-nlp-and-topic-modelling-tutorial)

### Week 6

Welcome to Week 6! Today, we will look at the answers to Assignment 1 and talk about your final projects. The distribution of who is presenting and when is online now (see below).

The main topic this week is machine learning. We will discuss the basics, training, testing data, and important libraries. This week should give you a good understanding of the more complex sentiment analysis and text classification we do in the next weeks. Preferably, you will also use these methods in the future.

An interesting paper is in this [link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4778120).

Also, check out these Kaggle notebooks;

[]()
[Titanic Solutions](https://www.kaggle.com/code/startupsci/titanic-data-science-solutions)
[Data Exploration](https://www.kaggle.com/code/pmarcelino/comprehensive-data-exploration-with-python)

### Week 7

Welcome to Week 7! We will combine data processing, text analysis, and machine learning to create our first real project that you can later be proud of! There are several objectives for this week that you should keep in mind.

- Can you import and analyze a dataset that you find on the internet? Are you able to use the necessary libraries or find them?
- Can you explore the data and find out important features? Can you communicate your findings through comments, graphs, and statistics?
- How do you deal with NaN's? What about generating new variables, like creating a profit variable out of costs and revenue? Do you understand different variable types, and can you convert them to one another? For example, can you convert a variable with Yes and No values to a binary variable?
- Can you preprocess a text dataset? Can you extract insights using nltk, SpaCy, gensim, and other libraries?
- Can you communicate your findings and create a story, which you then communicate to your audience?

These objectives are also key for your Assignment 2, which is distributed today and due on the night of 24.06. 

To an extent, I will also grade your final projects on the basis of these objectives.

Assignment 2: Datasets You Can Use (You can also find one yourself)

http://archive.ics.uci.edu/dataset/432/news+popularity+in+multiple+social+media+platforms

https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection

https://www.kaggle.com/datasets/nelgiriyewithana/mcdonalds-store-reviews

https://www.kaggle.com/datasets/prasad22/healthcare-dataset

https://sites.google.com/view/qanta/projects/diplomacy

https://github.com/niderhoff/nlp-datasets

### Week 8

Welcome to Week 8! This week, we will focus on the scientific properties of text data and text data for economic research that can be used as an outcome or treatment. Traditionally, we prioritize variables that are scientifically and objectively measurable. Text data, while challenging to quantify, can still be effectively used. This will enhance our understanding of these methodologies and hopefully help you during your final projects. I attached some of the older papers from previous weeks and some new ones for us to examine and discuss. We won't be coding so much this week, but I will let you work on your assignments during the second part of the seminar. Our discussions in the first half should be helpful to you.

Check out: constellate.org

IMPORTANT: Please write me an e-mail by 30.06.2024 on the topic of your final presentation. You can always change your subject, but it is essential for me to know how many people will end up presenting.

### Week 10

BS4: https://www.crummy.com/software/BeautifulSoup/bs4/doc/

Selenium: https://www.selenium.dev/documentation/

https://monashdatafluency.github.io/python-web-scraping/section-1-intro-to-web-scraping/

https://realpython.com/python-web-scraping-practical-introduction/

https://colab.research.google.com/drive/15uxrAeCCL327kWH9N0X-ogKwf2zErjP5

https://www.scrapethissite.com/

### Final Project
Your final project will be 75 \% of your grade overall, 15 \% being the presentations you will hold during the last two weeks, and 60 \% the final submission. Here is some additional information that might be useful for you.

#### Presentations

The presentations are aimed to help you and me in two ways. First, I require you to think about your projects earlier in the semester; that way, you do not cram to find an idea at the end of the semester. Second, by preparing a presentation and thinking about how much work you will do, you will better understand how to handle your final submission in advance.

- What is expected of you to present?
- What is your research idea? What are the hypotheses?
- What historical sources are you going to use?
- Which packages are you going to deploy?
- What is the overall workflow for you to complete this project?
- What does your "algorithm" look like? Could you explain your process to me without writing any code?
- Which loops are you going to use and why?
- What are you hoping to find out? Do you think your hypotheses will hold?

How will you present? It is primarily up to you to choose whether it is a standard slide-based presentation (LaTeX or PowerPoint) or a Jupyter Notebook (on GC).

#### Final Project
The final project will be most of your grade, where you bring your accumulated knowledge together. Our application sessions will help you understand which direction you should go. But here are some points that are relevant for you.

- I expect an entire project with data, descriptives, figures, and, most importantly, a story!
- It is up to you how far you will go with your analysis; advanced methods are optional; however, what you saw during the course is a must.
- Put all your data, notebook(s), and results in one folder if you decide to do it on your computer. Otherwise, GC should do the trick.
