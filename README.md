<h1 align="center" id="title">TTC Subway Delay Prediction</h1>

<p align="center"><img src="https://socialify.git.ci/MihirDharaiya/TTC-Subway-Delay-Prediction/image?forks=1&amp;issues=1&amp;language=1&amp;name=1&amp;owner=1&amp;stargazers=1&amp;theme=Light" alt="project-image"></p>

<p id="description">This project analyzes subway delays in Toronto's TTC (Toronto Transit Commission) system. It explores various factors such as delay duration station locations time of day and other key variables. The aim is to gain insights into the common causes and patterns of delays which could be useful for improving the system's efficiency.</p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Data Analysis: Conducts analysis on a dataset of TTC subway delays including columns like Date Time Day Station Code Min Delay Min Gap Bound Line and Vehicle.
*   Data Visualization: Utilizes Seaborn and Matplotlib to create visualizations that highlight trends and patterns in the data.
*   Database Interaction: Uses PostgreSQL (psycopg2) for data handling and querying in the project.
*   Predictive Modeling (optional if included): Applies machine learning models to predict the likelihood of future delays based on historical data.

<br/>
<h2>🛠️ Installation Steps:</h2>

<p>1. To run this project locally make sure you have the following dependencies installed:</p>

```
pip install numpy pandas seaborn matplotlib psycopg2
```
  <br/>
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Python
*   NumPy
*   Pandas
*   Seaborn
*   Matplotlib
*   PostgreSQL
*   psycopg2
<br/>
<h2>Dataset</h2>

The dataset used contains the following columns: 

Date: The date of the delay event. <br/>
Time: The time the delay occurred. <br/>
Day: The day of the week. <br/>
Station: The subway station where the delay occurred. <br/>
Code: Delay codes (such as signal issues equipment malfunctions etc.). <br/>
Min Delay: The duration of the delay in minutes. <br/>
Min Gap: The gap between subsequent delays. <br/>
Bound: Direction of the train. <br/>
Line: The subway line affected by the delay. <br/>
Vehicle: The vehicle ID involved in the delay.
