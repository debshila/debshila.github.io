# Hello!

Hi, I am Debshila. I am a researcher at OpenStax, an educational non-profit affiliated with Rice University, Houston, TX, USA. 

# Projects

Below are some of the data analysis and machine learning projects that I have been working on outside my work.

## Exploring Houston Restaurant Weeks

If you are a foodie in Houston, TX, then you look forward to this time of the year for the Houston Restaurant Weeks (HRW). A number of local restaurants come together to offer special menus and donate a part of each customer served to the Houston Food Bank. While this is a wonderful initiative, the information displayed on their website makes it difficult to search through. The overarching goal of this project is to aid HRW enthusiasts while they decide on which restaurants they want to visit this year.

- **Checkout the app:** https://debshila.shinyapps.io/exploring-houston-restaurant-weeks/


- Code: [HRW Github Repo](https://github.com/debshila/exploring-houston-restaurant-weeks)

## Gist do it! (Multilevel text summarizer)

People rarely read privacy policy documents. However, with the recent privacy breaches and GDPR coming into effect, individuals are recognizing the need to examine privacy policies that they previously blindly trusted. To facilitate examination of privacy policies, this web app basically generates summaries for privacy policy documents by selecting the most important sentences from these documents. The app leverages the textrank algorithm as implemented by the gensim package (https://radimrehurek.com/gensim/summarization/summariser.html).

In addition, the app displays the results of an Latent Dirichlet Allocation (LDA) based topic model (https://radimrehurek.com/gensim/models/ldamodel.html) trained on > 1000 privacy policy documents (https://usableprivacy.org/data), visualized using the pyLDAvis LDA visualizer (https://pyldavis.readthedocs.io/en/latest/readme.html#usage). This interactive illustration basically displays the underlying themes in privacy policy documents grouped into topics, the relationship amongst these topics (spatial proximity of the topics), and the top keywords from the topics.

- **Checkout the app:** [Gist do it!](http://gist-do-it.herokuapp.com)


- Code
    - [Gist do it App Repo](https://github.com/debshila/gist-do-it)
    - [Text-summarization Repo](https://github.com/debshila/multilevel-text-summarization)

