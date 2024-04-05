# Regression model XGBoost

Small demo of a linear regression model using XGBoost
The dataset used was [Student Performance](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)
I've applied an stratified sampling over the percentiles, just to show how it's done, if this was a production model I would've used another data point to do the stratified sampling, like for example what is considered a good/bad/average score in the given country's education system.
On top of using XGBoost the following tools were used:

 - sklearn: For the MAE scores.
  - pandas: For data preparation.
  - numpy: To ensure that the samples used to train/test the model are representative of the population.
  
  If you want to run this code:
  - First the code was written using Python 3.11.5
  - Use [Jupyter Lab](https://jupyter.org/install) or [Google Colab](https://colab.google/)
  - Clone this repository
	 ```
	 git clone https://github.com/EmanuelRiquelme/student-puntuation-regression
	 ```
  - Install the required libraries 
  ```
  pip3 install -q -r requirements.txt
  ```
  - To prepare the dataset go to data_preparation.ipynb
  - To train the model go to training.ipynb
