# Ploty-tutorials
Getting started again with plotly. 

This repo contains my exercies from various platforms on plotly. I will share personal projects soon in addition to what I learn with Dash

Kaggle link to the tutorial is here: https://www.kaggle.com/code/kanncaa1/plotly-tutorial-for-beginners/notebook

** Issues faced **
1. iplot failed this is because I had not installed chart_studio. To start with, pip install chart_studio (I'm using python 3)
2. chart_studio will require you to sign-in so use the offline version if you can or ignore chart_studio and rather rather import iplot from plotly.offline

** Plotly has 3 main modules:
>* plotly.plotly : actas an the interface between the local machine and Plotly
>* plotly.graph_objects : contains objects such as Figure, layout, data and plot definitions
>* plotly.tools(deprecate, plotly.subplots)

Plotly.express module can create the entire Figure at once. Inherently, it uses the graph_objects