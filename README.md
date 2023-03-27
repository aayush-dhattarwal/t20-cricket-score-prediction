# t20-cricket-score-prediction
The "T-20 Cricket Score Prediction" project is a machine learning model that predicts the score of a T-20 cricket match innings after the first five overs, using the Cricsheet dataset for model building. Cricsheet is a retrosheet for cricket that contains ball-by-ball details of all international and domestic cricket matches played worldwide. The project begins with exploratory data analysis (EDA) on the Cricsheet dataset to understand the data better and identify relevant features for modelling. After performing EDA, feature engineering is done to only consider the features that are useful for the model. The dataset is then split into training and testing sets to train and evaluate the model. Several machine learning algorithms are experimented with, and XG Boost algorithm is found to perform the best, achieving an R2 score of ~99% and a mean absolute error of ~1.6. The XG Boost model is then selected and deployed for score prediction. The user inputs data of the batting team at >5 overs, such as the number of runs scored, wickets lost, venue, batting team, bowling team and overs played. The model takes this input data and predicts the final score for the innings. The predicted score can help cricket teams to plan their strategy for the rest of the innings and make informed decisions. Overall, the "T-20 Cricket Score Prediction" project is a useful tool for cricket enthusiasts, coaches, and analysts to predict the score of a T-20 cricket match innings accurately.
 
# Dataset
https://www.kaggle.com/datasets/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s
# Project Website
https://aayush-dhattarwal-t20-cricket-score-prediction-app-68tiqn.streamlit.app/
# Demo Screenshots
![chrome_1yZGcHY5lb](https://user-images.githubusercontent.com/29508011/228030899-e18ee623-7cd4-44f0-9ff4-f01a11a1956d.png)
![chrome_FAGRSald0E](https://user-images.githubusercontent.com/29508011/228031072-77949c39-cf59-4383-a72f-5e7d6bc4d886.png)

# Tech Stack
•	Front-End: Streamlit

•	Back-End: Streamlit, Python

•	IDE: Jupyter Notebook, Pycharm

# How to run this app
1) Clone this repository

2) Create a virtual environment by using this series of commands:

 ----> pip install virtualenv > virtualenv myenv > myenv\Scripts\activate (for windows)

 ----> pip install virtualenv > virtualenv virtualenv_name > source virtualenv_name/bin/activate (for linux)

3) Copy all files from the cloned repo to newly created virtual environment folder.

4) Install all the packages by using the following command: pip install -r requirements.txt
 
5) Now for the final step. Run the app using this command: streamlit run app.py


