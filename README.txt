This project is my Capstone for BrainStation Data Science Boot Camp. In this project, I explored different NLP methods to process the 
Covid news article texts and predict article sentiment, including a Word2Vec embedding trained by my own neural network.

*This project spans across three different notebooks:
 1 - Fetch_Data_and_EDA
    - This notebook demonstrates my initial data cleaning/processing and EDA
    - Conda Environment to run this notebook: base
 2 - My_Own_Word2Vec 
    - This notebook docments how I trained my own Word2Vec embedding using neural network
    - Conda Environment to run this notebook: deeplearning
 3 - ML_Modeling
    - This notebook shows my modeling process using the cleaned data
    - Conda Environment to run this notebook: base

*The "environment" folder contains the .yml files for my Jupyter environment.
    - The base.yml environment applies to notebook 1 & 3
    - The deeplearning.yml applies to notebook 2

*The "data" folder contains several grid search results as well as the trained embedding modles that I use.
 - "my_own_w2v.pkl" is a dictionary storing my trained Word2Vec embedding
 -  The other files starting with "gridsearch" stores the few gridsearch results in my modeling process.
    More details can be found in the notebooks. 

*The dataset I used is requested from AYLIEN News web site: https://aylien.com/blog/free-coronavirus-news-dataset
 One will need to sign up with an email in order to request the data.

*A subset of the cleaned data, which I use for my modeling, can be acquired via the following link:
 https://drive.google.com/file/d/1dlXsDPOqUvSK3qAc7RSkyg4psq6jyp9j/view?usp=sharing



