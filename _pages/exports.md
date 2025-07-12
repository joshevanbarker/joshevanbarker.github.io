---
title: "Export Forecasting"
permalink: /portfolio/exports
---
![exports](/assets/images/Exports_Flask_App-1.png) <br><br>
In this project, using data from the International Trade Administration's Metropolitan Export Series (2005 - 2023), I followed export volumes of United States Metropolitan Statistical Areas (MSA) over time. Taking data from other sources, I meticulously cleaned the data and merged it into a unified dataset. I modeled how factors from general economic conditions to employment in the manufacturing sector, state policies like minimum wage and corporate income taxes, and exogenous factors like weather could impact export volumes. 

After training several machine learning models on the data, the best models were selected and incorporated into a Flask App user-interface, some of which is shown below. One useful tool was a form that could be manually filled by a user or automatically filled with the most recent data for each metro area. 

This project seeks to highlight my Python data cleaning, merging, and analysis skills, as well as my ability to create a custom user-interface to interact with the results. See a brief video demonstration of the application with some of its features here:

<video width="640" height="360" controls>
  <source src="/assets/audiovisual/Exports_Flask_App_Example.mp4" type="video/mp4">
</video>

To view all of the relevant code, visit the project's Github Respository here: <a href = "https://github.com/joshevanbarker/Machine_Learning_with_MSA_Exports">Machine_Learning_with_MSA_Exports</a>.
