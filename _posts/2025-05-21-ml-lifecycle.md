---
title: "What is the ML lifecycle"
author: anguzman
---
My last article was about "How skill sets are split between ML lifecycle roles". 

>> By the way you can check the article here : https://lnkd.in/deUprBsR

Today, I'll show you what exactly is the ML lifecycle concept and how It can ensure your company rocks in AI space.

ML lifecycle is the set of processes that makes an ML product successful. These are:

* Business problem and goal definition: A machine learning project begins with understanding the business objective. In machine learning analyst and business experts must first have a well-defined goal, always having into account client needs. They should ask themselves, is it really needed Machine learning here?. They can validate their approach by consulting datascientists.

* Data collection & preparation: Once the goal has been defined, the data collection process starts. Is data scraping required, or can we use existing company data sources?. Defining data extraction standards is essential to perform effective data cleansing and to minimize the incomplete data.

* Feature engineering, Model training and Model evaluation: Here it is where the data science work begins. It involves understanding the data (EDA process), measuring the importance of de features, setting up a baseline model, performing grid search and obtaining the first accuracy results. Data scientist will go back and forth in this process several times.

* Model deployment, Model serving and Monitoring: The ML Engineer is responsible for deploying the model selected by the data scientist. This may involve optimizing the model, deploying it as a microservice using an MLOps software stack, or enabling ¡new model versions to receive a portion of live traffic. In a production environment deploying thousands to hundreds of thousands of models on a Kubernetes presents additional challenges.

* Model maintenance: When the model is in production, issues with data processing can arise. Therefore, we need to monitor the model’s behavior over time. Two roles are typically involved here: ML Engineers, from an operational point of view, and Data Scientists, who focus on the architectural aspects. There are several types of model drift that can affect our model’s performance. We will treat them in a future release.

By understanding each phase of the lifecycle, teams can build ML systems that not only work, but deliver real, sustainable value.