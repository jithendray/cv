---
layout: page
permalink: /work
title: "Work"
---


### **Experience**

#### **Data Scientist, NeenOpal Inc., Nov 2020 - Present**

As a Data Scientist at [NeenOpal](https://www.neenopal.com/){:target="_blank"}, I spend (and have spent) most of my time on - applying my analytical skills to solve interesting real-world data problems, deriving insights and building data-driven solutions to improve the operational efficiency and quality of decision making for clients.

Projects I am working / have worked on:
* **ETL development:** Building a data warehouse on AWS RedShift for one of the largest multinational Logistics and Transportation company in Sri Lanka. Developing automated python-based pipelines and AWS-Glue jobs build robust data pipelines.
* **Demand Forecasting and Inventory Management:** Leveraged machine learning to predict the sales at store and SKU level(500+ stores and 1000+ SKUs) for one of the largest Tiles producers in Sri Lanka.
* **Employee Scoring:** Analyzed monthly performance of Marketing / Recovery officers of a leading NBFC in Sri Lanka and built Tableau dashboards to help the stakeholders to quickly gain insights into the performance of their employees.

#### **Undergrad Research Assistant, IIIT Allahabad, May 2019 - Jul 2019**

As a research assistant under Prof. Anupam Agrawal's guidance, I performed literature survey for research on early detection of Autism in toddlers. Designed a system which analyses eye gaze patterns and accurately detects whether a toddler has autism.



### **Projects**
See here for complete list of my projects - [Portfolio](https://jithendrabsy.github.io/portfolio/){:target="_blank"}


#### **FPGA Neural Network Accelerator**
[[github](https://github.com/tirumalnaidu/opencl-hls-cnn-accelerator){:target="_blank"}]


Designed a Neural Network Accelerator for Darknet Reference Model (which is 2.9 times faster than AlexNet and attains the same top-1 and top-5 performance as AlexNet but with 1/10th the parameters) for image classification on Imagenet Dataset on Intel Cyclone V Soc FPGA, while working as a part-time undergrad researcher under guidance of [Prof. Vinod Kumar Jain](https://sites.google.com/view/dr-vinod-kumar-jain/home?authuser=0){:target="_blank"}. When connected to ARM Cortex A9 processor using OpenCL framework, it achieved around 300% faster inference speed than CPU.

#### **AWS SageMaker - Fraud Detection**
[[github](https://github.com/jithendrabsy/aws-SageMaker-fraud-detection){:target="_blank"}]


The goal of this project is to underdstand the complete machine learning work flow (from data collection, data storing, data preprocessing, model selection, training and finally to model deployement) using AWS SageMaker. I built an end to end fraud detection service system using services provided by AWS. Trained machine learning job and deployed model using SageMaker, created endpoint that can be invoked by Lambda, created API with API Gateway in order to send request to flask application. Deployed the application on AWS Cloud9 environment and finally integrated the application with SNS service to alert client by sending email when fraud is detected.



#### **Heartbeat anomaly detection**
[[github](https://github.com/jithendrabsy/mini-projects/tree/main/heart-ECG-anomaly-detection){:target="_blank"}]
[[nbviewer](https://nbviewer.org/github/jithendray/mini-projects/blob/main/heart-ECG-anomaly-detection/AutoEncoder_AnomalyDetection.ipynb){:target="_blank"}]


Detected anomalies in heartbeats using LSTM Auto-encoder. The dataset used contains 5000 time series sequences with 140 timestamps obtained with ECG and corresponds to heartbeats from a single patient. Trained and evaluated autoencoder, chose a threshold for anomaly detection and finally classified unseen examples as normal or anomaly.



#### **Forecasting Air pollution**
[[github](https://github.com/jithendrabsy/forecasting-air-pollution){:target="_blank"}]


In this project, I explored various models for forecasting time series. I then compared the performance of the models over two different metrics. I forecasted the amount of pollution in air based on the historical pollution data. I used Beijing pollution public dataset - which contains data from 2010-14, along with extra weather features such as temperature, windspeed, pressure etc.




#### **Buy or Sell Stocks? - Dual Moving Average Crossover (DMAC) trading strategy**
[[nbviewer](https://nbviewer.org/github/jithendray/mini-projects/blob/main/buy-or-sell-stocks/MARUTI_DMAC.ipynb){:target="_blank"}]


Predicted when to buy or sell stocks using simple dual moving average crossover strategy. And then backtested it over 5 years of stock. I used Yahoo! finance data downloader to download the stocks of Maruti Suzuki (MARUTI.NS). A return of 113% in 5 years estimated by DMAC strategy with short and long windows 13 and 48 respectively. However - It is up to the trader to choose the number of days to which the two moving averages are set. This should be done after testing and evaluating the system thoroughly in the recommended way, using the trader’s method.




