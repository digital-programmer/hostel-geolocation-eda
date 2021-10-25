# Objective 
This project involves the use of K-Means Clustering to find the best accommodation for students in Bangalore (or any other city of your choice) by classifying accommodation for incoming students on the basis of their preferences on amenities, budget and proximity to the location.

# Project Stages

The project consists of the following stages:<br>

<img src="./results/workflow.png" alt="workflow" width="700px" height="400px">

# Steps
1. Fetch Datasets from the relevant locations (Data Collection)

2. Clean the Datasets to prepare them for analysis. (Data Cleaning via Pandas)

3. Visualise the data using boxplots. (Using Matplotlib /Seaborn /Pandas) 
   <br>
   
   <img src="./results/boxplot.png" alt="boxplot" width="700px" height="400px"> <br>
   
   <img src="./results/elbow_curve.png" alt="elbow_curve" width="700px" height="400px">

4. Fetch Geolocational Data from the Foursquare API. (REST APIs) 

5. Use K-Means Clustering to cluster the locations (Using ScikitLearn) <br>

   <img src="./results/bargraph.png" alt="bargraph" width="700px" height="400px">

6. Present findings on a map. (Using Folium/Seaborn)
   <br>
   
   <img src="./results/map.png" alt="map" width="700px" height="400px">
