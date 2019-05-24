## Objective
This project demonstates the combination of time-series analysis and machine learning algorithms to predict the occurrence of next earthquake using the seismic wave data provided. 
## Introduction
A large focus of Earth science research belongs to forecasting the timing and severity of earthquakes. Earthquakes are notoriously difficult to predict and can have devastating impact on those unfortunate enough to experience one. One of the few predictors of earthquakes known to scientists is overall seismic activity measured from vibrations caused by movement in tectonic plates in the earth's crust. Los Alamos National Laboratory (LANL) is an organization studying the predictive effects of seismic waves leading up to an earthquake. Forecasting an earthquake has obvious health and financial incentives for society as a whole and should be addressed as a priority. Our goal is to forecast when the next laboratory earthquake will take place based on seismic data using time series analysis and machine learning techniques.
<p>In this study, stochastic models known as auto regressive integrated moving average (ARIMA) models in combination with a linear regression were used to predict the timing of lab generated earthquakes. We construct a reduced time series from the original dataset and perform exploratory analysis for a basis to start modeling. An appropriate ARIMA model is fit to the time series and then used to provide predictions of seismic data. Finally, those predictions are fed to a linear regression to predict time_to_failure.
## Learnings
This project has been extremely challenging right from getting to know the dataset, to coming up with a strategic approach, till the very end of submitting the report of project. We all knew the challenges of working with this dataset and we accepted the challenge hoping to learn much more by our efforts. I feel very happy to share that we learned a lot more than what we expected. 
<p>Geophysics was a new domain to us and getting to know the terminologies used, reading the research papers in this field to get an idea of what is happening in this field currently was challenging and a learning experience as well. Another challenge was working with the data itself since it contains more than 600 million records. To read and come up with strategy of averaging the chunks of data took some time. Then the next challenge was to come up with a model that can predict the time_to_failure using just seismic data. This required a lot of brainstorming and reasoning power to come-up with an effective strategy. Then I also got to apply advanced ml algorithms along with timeseries to see if anything works good for us. In the end, although we were not able to produce any predictive power with our models, we learned a lot through our continuous efforts to get the model working.
