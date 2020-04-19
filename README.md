# Determinants of pricing

Understanding pricing and forecasting prices is a task that is important in many industries. In this analysis I focus on the analysis of Airbnb prices in Seatle and examine which determinants have an impact on prices. For this purpose, I use various descriptive analyses to create a machine learning model, in which I rank the available feautures according to their relevance. 

Corresponding blog post exits to this analysis, in which the results are discussed more explicitly: 
https://medium.com/@ashraf.menteribrahim/neighbourhood-type-of-property-or-tv-which-factor-influences-airbnb-prices-in-seatle-5bd8fb0296ae

# Data 
For this analysis I took the Airbnb data of the year 2016 for the city of Seatle. This basis contains more than 3000 entries and nearly 100 features. 

# Steps of Analysis 
1) Understanding the features </br>
 1.1) Clear up data</br>
 1.2) select relevant features </br>
 1.3) and create new features  </br>
2) Training Machine Learning Model </br>
 2.1) RandomForrest-Regressor </br>
 2.2) Cross Validation & Grid Search Hyperparameter Tuning</br>
 2.3) Rerunning and evaluating the Final Model</br>
 2.4) Extracting top Features </br>
 
# Model Performance 
  - R^2: .63</br>
  - MAE: ~31</br>
  
 # Dependencies 
 - Python 3 </br>
 - Pandas </br>
 - Numpy </br>
 - Sklearn </br>
 - os</br>
 - time </br>
 - Sklearn </br>
 - Matplotlib </br>
 - Seaborn </br>

