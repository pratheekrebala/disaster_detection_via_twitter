#Disaster Detection via Twitter

This repository contains a predictive classification model I developed for determining if a Tweet is discussing a disaster event or not (i.e., building collapse, wildfire, terrorist attack) as a capstone project for the Data Science course offered at General Assembly in Austin, TX. The course was excellent and I highly recommend it to anyone interested. 

**Form**: The project is in a **long** python notebook ([disaster_detection_via_twitter.ipynb](disaster_detection_via_twitter.ipynb)) which can be viewed directly via the GitHub website. Alternatively, it can be viewed via the online Jupyter notebook viewer ([click here](https://nbviewer.jupyter.org/github/rjadrich/disaster_detection_via_twitter/blob/master/disaster_detection_via_twitter.ipynb)). For brevity, feel free to just read the descriptions and ignore the long code segments. There is a total of eight sections with figures and plots interspersed throughout. 

**Outcome**: combining various Natural Language Processing tools, an accurate Logistic Regression classifier is built to automatically identify a Tweet as a disaster or not. The model boasts an 8-fold cross validation accuracy of roughly 87% and a receiver operating characteristic (ROC) area of 0.94.

This project is still under development. In particular, I wish to create a Heroku app to monitor real-time tweets and classify them as pertaining to a disaster or not. This tool may be freely used and improved upon (in fact this is encouraged). If any improvements on the model are made please let me know.




