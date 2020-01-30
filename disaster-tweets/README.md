### Disaster Tweets Kaggle Competition

**The Challenge:** Predict whether there is a real disaster using the content of social media posts.

**The Motivation:** A number of organizations, including disaster relief and news outlets, actively monitor social media platforms for information about events. Detecting whether these events are real disasters based on the content of social media posts allows these organizations to deploy resources efficiently.

**Key Lessons:** This was my first foray into NLP. I learned that data pre-processing for NLP is a whole different beast than for typical classification/regression problems. This challenge also encapsulated fewer features than what I'm used to, which emphasized the importance of building a model that could extract meaning from the one main text field. Finally, I learned all about the NLP kingpins, including GloVe, ELMo and BERT. After unsucessfully playing around with GloVe and realizing its shortcomings, I implemented a basic model using pre-trained BERT plus one dense layer. I tried (and failed) to get my local Jupyter instance to hook into my GPU so instead I ran the code using Kaggle kernel so that I could create an output file to submit to the competition.

**Links to My Work:**

* 1: [Exploratory Data Analysis](https://github.com/amypeniston/kaggle-competitions/blob/master/disaster-tweets/1_EDA.ipynb)
* 2: [Data Cleaning](https://github.com/amypeniston/kaggle-competitions/blob/master/disaster-tweets/2_Data_Cleaning.ipynb)
* 3: [Model Experimentation](https://github.com/amypeniston/kaggle-competitions/blob/master/disaster-tweets/3_Model_Experimentation.ipynb)
* 4: [BERT Model](https://github.com/amypeniston/kaggle-competitions/blob/master/disaster-tweets/4_BERT.ipynb)

**Link to Kaggle:** [https://www.kaggle.com/c/nlp-getting-started](https://www.kaggle.com/c/nlp-getting-started)