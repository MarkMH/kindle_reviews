![](https://github.com/MarkMH/kindle_reviews/blob/a5c05a0a7d98148b6dbe609ac0fe02ac1437e821/images/banner_blanco.png)

<p align="justify" style="text-align:justify"> 
In this project, supervised machine learning methods are used to predict whether an previously unseen Amazon Kindle Book Review is positive or negative based on its text content. The text analysis is done in Python and is performed on 1,000,000 reviews available on https://www.kaggle.com/datasets/bharadwaj6/kindle-reviews.    
</p>


<p align="justify" style="text-align:justify"> 
The text preprocessing requires the nltk module, which may need to be installed manually. Note that the code below was developed for Google Colab. Should you want to use the same lines, make sure that the data is stored in a folder called "data".   
</p>

![](https://github.com/MarkMH/kindle_reviews/blob/a5c05a0a7d98148b6dbe609ac0fe02ac1437e821/images/carbon_load_data.png)

---

<p align="justify" style="text-align:justify"> 
The most important preprocessing steps are performed by the <i>prep</i> function. Note that the order of the steps is important, especially that in step three the data frame changes substantially. Before step three we are dealing with a list of strings, whereas after step three each string has been decomposed into a list of words. </p> 

![](https://github.com/MarkMH/kindle_reviews/blob/a5c05a0a7d98148b6dbe609ac0fe02ac1437e821/images/carbon_preprocessing.png)

---

The function <i>prep</i> is work in progress and updated continuously, if you are interested in the current state of this function, just contact me. I'm happy to share my code and always welcome comments.</p>
