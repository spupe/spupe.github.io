---
title: "Good Train Bad Train"
date: 2022-06-15
# externalUrl: "http://goodtrainbadtrain.herokuapp.com"
summary: "Predict whether long-range train rides in Germany will be delayed, using a machine learning model. Key tools: Python, pandas, folium, Scikit-learn, Heroku, Streamlit, GCP. [Live Demo](http://goodtrainbadtrain.herokuapp.com), [GitHub](https://github.com/Good-Train-Bad-Train/gtbt)"
showReadingTime: false
_build:
  render: "false"
  list: "local"
---

Our initial dataset was composed of all train rides between Cologne, Berlin and Munich in the past 2 years. We then engineered several features from it - flags for holidays and Covid lockdown periods, day of the week and month, average train delay in a given route, etc. - and combined that with historical weather data. We trained a LightGBM model on these features, and it reached an accuracy of 78% on previously unseen test data. 

We offered the result of our prediction along with other key data in an user-friendly interface connected with APIs from a meteostat.net, Deutsche Bahn and our own model, hosted on GCP - you can see a live demo on the link below. This project was a result of a two-week sprint at the end of a 400h Data Science course at Le Wagon, and a collaboration between me and my colleagues Marie Macnee, Boris Bohsem and Juan Cotrino.

Key tools: Python, pandas, folium, Scikit-learn, Heroku, Streamlit, GCP.
 
[Live Demo](http://goodtrainbadtrain.herokuapp.com)

[GitHub](https://github.com/Good-Train-Bad-Train/gtbt)


