# Predicting Oscars 2020 winner of Best Picture Award<br>
<img src = "oscar.png" align = "middle" width = "80">
This project served as a Capstone project for the Springboard Data Science Bootcamp. The project involved building an entire data science pipeline for collecting the most reliable publicly available data for moedling and predicting the Best P_icture Awasrd at the 92nd Academy Award due to be held on February 9th. The various Notebooks are:

1. **Data Acquisition**: Acquiring data from Wikipedia and IMDB using their respective APIs and extracting the necessary information using BeautifulSoup() and Regular Expressions librarries in Python. 
2. **Data cleaning and wrangling**: Normalized box-office and budget information, adjusted for inflation, removed spurious information, estimate missing information like budget and box office (especially for 2019 movies) with Lasso Regression technique. Performed Feature engineering to quantify the strength of movie (Oscar score) based on past accolades of cast, crew,. director, writer and producers at the Academy Awards. 
3. **Data Visualization**: Movies from over 6 decades (1960 to 2018) were ranked acording to aggregate score based on Academy Award performences and IMDB ratings by fans. We checked for creelations between IMDB ratings, Oscar score, budget, box office and genres.
4. **Predictive Modeling**: Several machine learning algorithms (Logistic Regression, K Nearest neighbors, Random Forest with Bagging and Boosting, Neural Networks, and Ensemble methods) were used to make predictions, based on which a grand average of probabilities was calcutated to predict the Best Pucture winner. 
<img src = "oscar_predict.png">

