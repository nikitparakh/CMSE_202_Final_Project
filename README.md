# CMSE_202_Final_Project

Final Project: Business Affected by COVID-19

HOW TO RUN CODE:

1. Dataset to run our code can be found here:https://www.yelp.com/dataset along with the documentation here:https://www.yelp.com/dataset/documentation/main.

2. Make sure you download the main dataset which is a json file: yelp_academic_dataset_business.json

3. Make sure you have Basemap installed. Documentation here: https://matplotlib.org/basemap/
A simple way would be to use "conda install basemap"

4. Folium is used for one of the visuals along with the us-states.json we used earlier in the year.
documentation here:https://python-visualization.github.io/folium/
simple way : "pip install folium"
us-states.json here: https://raw.githubusercontent.com/python-visualization/folium/master/examples/data/us-states.json

5. The model is already stored in a file : predict_open_pca.p. It is loaded into the jupyter notebook using pickle. If you wish to train the model again, just set the variable "rerun" to True.

Vinny Barile - created visuals including the seaborn plots,folium map and the map using basemap.
Ryan Patrick Mulligan and Nikit Parakh - cleaned the dataset and created the SVM model and performed PCA on it using sklearn.
