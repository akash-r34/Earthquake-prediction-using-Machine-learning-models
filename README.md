# Earthquake-prediction-using-Machine-learning-models

A project done for the course CSE3505 - Essentials of Data Analytics under <b>ELANGO N M</b>

<h3>Team members</h3>
<ul>
<li><b>AKASH R 20BCE1501</b> Github: <a href="https://github.com/akash-r34">akash-r34</a></li>
<li><b>ARJUN BHARANI 20BCE1505</b> Github: <a href="https://github.com/ArjunBharani">ArjunBharani</a></li>
<li><b>SHIVAM SHARMA 20BCE1442</b> Github: <a href="https://github.com/shivams-23">shivams-23</a></li>
<li><b>AKSHAY GIRISH 20BCE1573</b> Github: <a href="https://github.com/Akshaykviit023">Akshaykviit023</a></li>
</ul>
<h2>Abstract</h2>
This project aims to predict the magnitude and probability of Earthquake occurring in a particular region from the historic data of that region using various Machine learning models.

<h2>Dataset</h2>
The dataset used in this project is called the "SOCR Earthquake Dataset," and it contains information about earthquakes that have occurred with a magnitude of 3.0 or greater worldwide.

Each row in the dataset represents a single earthquake event and includes the following information:

<ul>
<li>Date and time of the earthquake in UTC (Coordinated Universal Time)</li>
<li>Latitude and longitude(in degree) of the epicenter, which is the point on the Earth's surface directly above where the earthquake occurred</li>
<li>Depth of the earthquake, measured in kilometers</li>
<li>Magnitude of the earthquake on the Richter scale</li>
<li>SRC = source</li>
<li>nst - number of stations used for solution (range: 0 to ...)</li>
<li>close - distance of closest station to epicenter (range: 0 to ...)</li>
<li>rms - root-mean-squared residual of solution (range: 0. to 1.)</li>
<li>gap - azimuthal gap (range: 0 to 360)</li>
</ul>

The Richter scale is a logarithmic scale that measures the magnitude of an earthquake based on the energy released by the earthquake. Each increase of one unit on the Richter scale represents a tenfold increase in the amplitude of the seismic waves generated by the earthquake.<br>

The dataset contains earthquake events from January 2, 2017, to December 31, 2019, which includes a total of 37,706 earthquakes. This dataset could be used for a variety of purposes, such as studying earthquake patterns and trends over time or for predicting future earthquake activity

<h2>Introduction</h2>
The SOCR Earthquake Dataset can be used to build machine learning models to predict earthquakes or to better understand earthquake patterns and characteristics. Here are a few possible ways machine learning models can be used with this dataset:
<br>
<br>
<ol>
<li>Earthquake prediction: You can use this dataset to build a model that predicts when and where an earthquake might occur based on past earthquake data. You could use techniques such as time series analysis, clustering, or classification to identify patterns in the data and make predictions.</li>

<li>Magnitude prediction: You can use this dataset to build a model that predicts the magnitude of an earthquake based on other factors such as location, depth, or the number of seismic stations that recorded the earthquake. You could use regression techniques to build this model.</li>

<li>Risk assessment: You can use this dataset to identify areas that are at higher risk of earthquakes based on historical earthquake data. You could use clustering or classification techniques to identify patterns in the data and identify areas with similar characteristics.</li>

<li>Anomaly detection: You can use this dataset to detect anomalies or outliers in the data, which could represent earthquakes that are unusual or unexpected. You could use techniques such as clustering or classification to identify patterns in the data and detect anomalies.</li>

<li>Data visualization: You can use this dataset to create visualizations of earthquake data, which could help you identify patterns and relationships in the data. You could use techniques such as scatter plots, heat maps, or geographic information systems (GIS) to visualize the data.</li>
</ol>
<br>
These are just a few examples of the many ways that machine learning models can be used with the SOCR Earthquake Dataset. The specific approach you take will depend on your research question and the goals of your analysis. In this project we focus mainly on Earthquake prediction and Magnitude prediction.
<br>
<h2>Class diagram</h2>
<img src="https://user-images.githubusercontent.com/113085803/229195883-8aec511d-0e24-46c4-8cd2-67e4bdfb759c.png"/>
