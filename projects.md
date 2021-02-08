---
layout: default
---

[Professional experience](./professional-experience.html) | Projects | [Blog articles](./blog-articles.html) | [Contact](mailto:cochenercamille@yahoo.fr)

## Project Portfolio

<p style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif; font-size:18px; background-color : #16af9d; color: white ; padding-left: 10px; border-radius: 10px;">Hackathon Ecole Polytechnique/Carrefour (Rank: 1st) - Marketing Mix Modeling</p>

<img src="assets/img/calendar.png" 
  style="vertical-align: middle ; padding: 5px" 
  width="20"> <i>From February 2020 to April 2020 - 2 months</i><br>

<span style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif;"><u>Objective</u> : to build a local Marketing Mix Modeling (MMM) in order to analyze and predict the impact of marketing media on sales (ROI)</span>

<p style="text-align: justify;">I took part in the annual hackathon organized by the "Next Gen RetAIl" chair at <a href="https://www.polytechnique.edu/">Ecole Polytechnique</a>, which gathered 132 students in 26 teams. During this challenge, <a href="https://www.carrefour.fr/">Carrefour</a>, the sponsor of the chair, proposed 3 study themes: building the optimal product DNA of a shop, designing a Local MMM and optimizing the frequency and packaging of in-store supplies.  </p>

<p style="text-align: justify;">My team won the hackathon by proposing a MMM with a local granularity that focuses specifically on organic products. Our model allows to determine the business drivers of organic product sales. </p> 

<span style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif;">What is a MMM ?</span>

<p style="text-align: justify;">Marketing Mix Modeling studies the relationships between marketing spending and business performance (i.e. revenue, sales) to determine business drivers and estimate return on investment (ROI). It helps marketing experts to better allocate their budgets on marketing channels. </p> 

<img src="assets/img/MMM.png" 
  style="vertical-align: middle" >

<p style="text-align: justify;">To build our model, we had access to more than 30 historical datasets on all products, purchases, marketing investments and sales of Carrefour shops. Using these, we were able to train a very efficient Machine Learning algorithm, <a href="https://catboost.ai/">CatBoost</a>, and then interpret it using <a href="https://shap.readthedocs.io/en/latest/">Shapley values</a>. The results were presented in the form of a user-friendly dashboard built with <a href="https://plotly.com/dash/">Dash</a>.</p>

<p style="text-align: justify;">The hackathon ended with a pitch session during which we provided recommendations that were in line with the <a  href="https://www.carrefour.com/fr/groupe/transition-alimentaire">food transition objectives</a> of the company to a jury of Carrefour directors.</p>

<p style="text-align: center;"><a href="https://github.com/camillecochener/Hackathon-X-Carrefour-2020" rel="nofollow noopener noreferrer"> <i class="fab fa-github" style="padding: 5px"></i>Details on Github</a> <a href="https://www.polytechnique.edu/en/content/hackathon-chair-next-gen-retail-comes-end" rel="nofollow noopener noreferrer"><i class="far fa-newspaper" style="padding: 5px"></i>Article - Polytechnique</a> <a href="https://www.telecom-paris.fr/telecom-paris-remporte-hackathon-x-carrefour-ai-data-science" rel="nofollow noopener noreferrer"><i class="far fa-newspaper" style="padding: 5px"></i>Article - Télécom Paris</a></p>


<p style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif; font-size:18px; background-color : #16af9d; color: white ; padding-left: 10px; border-radius: 10px;">Toxic Comment Classification Challenge - NLP</p>

<img src="assets/img/calendar.png" 
  style="vertical-align: middle ; padding: 5px" 
  width="20"> <i>From March 2020 to June 2020 - 3 months</i><br>

<span style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif;"><u>Objective</u> : to build a multi-headed model that’s capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models.</span> 

<p style="text-align: justify;">The <a href="https://www.perspectiveapi.com/">Perspective API</a> uses Machine Learning to identify abusive comments. It is the product of a collaborative research effort operated by <a href="https://jigsaw.google.com">Jigsaw</a> and Google’s Counter Abuse Technology team, named <a href="https://conversationai.github.io/">Conversation AI</a>. They made their data available as part of a <a href="https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview">Kaggle challenge</a> (2018) to enhance research about this topic and improve the tools to combat online toxicity and harassment.</p> 

<p style="text-align: justify;">In this competition, we have to build a multi-label model to detect the toxicity of a sentence using a dataset of about 160k comments from Wikipedia’s talk page edits.</p> 

<span style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif;">What is a multi-label classification model ?</span>

<p style="text-align: justify;">Multi-label classification is a variant of classification problem where multiple labels could be assigned to each instance. On the contrary, a multiclass classification is a single-label problem in which instances are categorized into precisely one class. </p>


<p style="text-align: justify;">In our study, several deep learning approaches were tested and compared : Logistic regression (LR), Long Short-Term Memory Networks (LSTM), Convolutional Networks (CNN) combined with language processing techniques (NLP) and word representation methods (Word Embedding). Our final selected model was a bi-directional LSTM neural network. The results of this model were excellent: the AUC score obtained was 98%.</p>

<img src="assets/img/Resultats Kaggle NLP.png" 
  style="vertical-align: middle" width="400">

<i>Note : As we participated in this competition as a "late submission", we couldn't obtain a ranking.</i>

To go further, we've built a user-friendly application using <a href="https://plotly.com/dash/">Dash</a> to serve our model which could be deployed on <a href="https://www.heroku.com/">Heroku</a> for example. 

<img src="assets/img/appli.gif" 
  style="vertical-align: middle" >

<p style="text-align: center;"><a href="https://github.com/camillecochener/Toxic-comment-classification-challenge" rel="nofollow noopener noreferrer"> <i class="fab fa-github" style="padding: 5px"></i>Details on Github</a></p>

<p style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif; font-size:18px; background-color : #16af9d; color: white ; padding-left: 10px; border-radius: 10px;">Hackathon QMI/LFIS/Dauphine (Rank: 4th) - Machine Learning for Asset Management</p>

<img src="assets/img/calendar.png" 
  style="vertical-align: middle ; padding: 5px" 
  width="20"> <i>February 2020 - 24h challenge</i><br>


<p style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif; font-size:18px; background-color : #16af9d; color: white ; padding-left: 10px; border-radius: 10px;">To build a resilient ETL to analyze GDELT database - Data Engineering</p>

<img src="assets/img/calendar.png" 
  style="vertical-align: middle ; padding: 5px" 
  width="20"> <i>From December 2019 to February 2020 - 2 months</i><br>


<p style="font-weight: bold; font-family: 'Yanone Kaffeesatz', sans-serif; font-size:18px; background-color : #16af9d; color: white ; padding-left: 10px; border-radius: 10px;">Bike Sharing Predictions - Machine Learning with Spark</p>

<img src="assets/img/calendar.png" 
  style="vertical-align: middle ; padding: 5px" 
  width="20"> <i>October 2019 - 1 week</i><br>


[Back to homepage](./)
