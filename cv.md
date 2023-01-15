---
layout: page
permalink: /cv/
title: "CV"
comments: false
---

### **Experience**

#### **Data Engineer, NeenOpal Inc., Jun 2021 - Present**
**Enterprise wide BI Implementation for a Large Multinational Logistics Company**

+ Developed End to End Data Warehousing solution
- Setup of Data Warehouse on AWS Redshift
- Configured ETL Pipelines for Migration of data from S3 to RedShift using AWS Glue & Lambda
- Trigger Refresh of data in the 50+ PowerBI dashboards developed as part of the project - helping stakeholders to quickly gain insights across various departments
+ Led multiple requirement-gathering sessions with the client’s business and technical teams across various departments to understand the data better and define important logistic KPIs
+ Developed complex SQL queries to transform raw tables into insightful data for powering PowerBI dashboards.
+ Led daily scrum calls and contributed to the improvement of development processes

**End-to-End Business Intelligence Implementation (AWS + Tableau) for an Edtech Company**

+ Led a team of 3 Data Engineers for the development of ETL jobs for migration of data from Aurora to Amazon Redshift using AWS Glue
+ Reduced the manual effort by 20% through implementing ETL job failure trigger emails using EventBridge, SNS, and Lambda
+ Responsible for continuous QC and Performance Monitoring of the Daily ETL Scripts and timely resolution in case of any errors


#### **Data Scientist Intern, NeenOpal Inc., Nov 2020 - May 2021**

**Demand Forecasting and Inventory management for a Tiles Manufacturing Company**
+ Responsible for developing a hybrid forecasting model (Leveraging ML algorithms and statistical models) in order to predict the sales at the SKU-Store level for 400+ stores and 1000+ SKUs of one of the largest Tiles producers.
+ Responsible for automating the entire pipeline including - automatic forecast generation and dashboard refresh with the latest data


**Marketing and Recovery Officer scoring project for a leading NBFC client**
+ Developed a comprehensive scoring model for Marketing and Recovery Officers by combining various key features affecting the score.
+ Built a Tableau dashboard with scores and other details to streamline the ranking process for officers

#### **Undergrad Research Assistant, IIIT Allahabad, May 2019 - Jul 2019**

As a research assistant under Prof. Anupam Agrawal's guidance, I performed literature survey for research on early detection of Autism in toddlers. Designed a system which analyses eye gaze patterns and accurately detects whether a toddler has autism.



### **Projects**
See here for complete list of my projects - [Portfolio](https://jithendray.github.io/portfolio/){:target="_blank"}


#### **FPGA Neural Network Accelerator**
[[github](https://github.com/tirumalnaidu/opencl-hls-cnn-accelerator){:target="_blank"}]


Designed a Neural Network Accelerator for Darknet Reference Model (which is 2.9 times faster than AlexNet and attains the same top-1 and top-5 performance as AlexNet but with 1/10th the parameters) for image classification on Imagenet Dataset on Intel Cyclone V Soc FPGA, while working as a part-time undergrad researcher under guidance of [Prof. Vinod Kumar Jain](https://sites.google.com/view/dr-vinod-kumar-jain/home?authuser=0){:target="_blank"}. When connected to ARM Cortex A9 processor using OpenCL framework, it achieved around 300% faster inference speed than CPU.

#### **AWS SageMaker - Fraud Detection**
[[github](https://github.com/jithendray/aws-SageMaker-fraud-detection){:target="_blank"}]


The goal of this project is to underdstand the complete machine learning work flow (from data collection, data storing, data preprocessing, model selection, training and finally to model deployement) using AWS SageMaker. I built an end to end fraud detection service system using services provided by AWS. Trained machine learning job and deployed model using SageMaker, created endpoint that can be invoked by Lambda, created API with API Gateway in order to send request to flask application. Deployed the application on AWS Cloud9 environment and finally integrated the application with SNS service to alert client by sending email when fraud is detected.



#### **Heartbeat anomaly detection**
[[github](https://github.com/jithendray/mini--projects/tree/main/heart-ECG-anomaly-detection){:target="_blank"}]
[[nbviewer](https://nbviewer.org/github/jithendray/mini-projects/blob/main/heart-ECG-anomaly-detection/AutoEncoder_AnomalyDetection.ipynb){:target="_blank"}]


Detected anomalies in heartbeats using LSTM Auto-encoder. The dataset used contains 5000 time series sequences with 140 timestamps obtained with ECG and corresponds to heartbeats from a single patient. Trained and evaluated autoencoder, chose a threshold for anomaly detection and finally classified unseen examples as normal or anomaly.



#### **Forecasting Air pollution**
[[github](https://github.com/jithendray/forecasting-air-pollution){:target="_blank"}]


In this project, I explored various models for forecasting time series. I then compared the performance of the models over two different metrics. I forecasted the amount of pollution in air based on the historical pollution data. I used Beijing pollution public dataset - which contains data from 2010-14, along with extra weather features such as temperature, windspeed, pressure etc.




#### **Buy or Sell Stocks? - Dual Moving Average Crossover (DMAC) trading strategy**
[[nbviewer](https://nbviewer.org/github/jithendray/mini-projects/blob/main/buy-or-sell-stocks/MARUTI_DMAC.ipynb){:target="_blank"}]


Predicted when to buy or sell stocks using simple dual moving average crossover strategy. And then backtested it over 5 years of stock. I used Yahoo! finance data downloader to download the stocks of Maruti Suzuki (MARUTI.NS). A return of 113% in 5 years estimated by DMAC strategy with short and long windows 13 and 48 respectively. However - It is up to the trader to choose the number of days to which the two moving averages are set. This should be done after testing and evaluating the system thoroughly in the recommended way, using the trader’s method.


<h2>Skills</h2>

<ul class="skill-list">
	<li>Python</li>
	<li>PySpark</li>
	<li>SQL</li>
	<li>AWS - Redshift, Lambda, Glue, S3, EC2</li>
	<li>Snowflake</li>
	<li>Apache Airflow</li>
	<li> NumPy, Pandas, scikit-learn, matplotlib,Excel, Tableau</li>
	<li>PyTorch</li>
	<li>Time Series Analysis and Forecasting</li>
	<li>Scala</li>
	<li>R</li>
</ul>


### **Education**


#### **Bachelors**

I studied **Computer Science and Engineering** at Indian Institute of Information Technology, Jabalpur.

* During my undergraduation, We [designed](https://github.com/tirumalnaidu/opencl-hls-cnn-accelerator){:target="_blank"} a CNN accelerator on Intel DE10 Nano FPGA.
* At some other point during my undergraduation, I did a Research Internship at the Human Computer Interaction lab (HCI), Indian Institute of Information Technology - Allahabad, where I was supervised by Prof. Anupam Agrawal.
* I was a Co-coordinator for the Photography Club - ShutterBox. I covered various technical and cultural events in the campus during 2017-2018.


Some of the classes I took
* **Computer Science:** Fundamentals of Computing (with C), Object-oriented Programming (with Java), Data Structures, Design & Analysis of Algorithm, Database Management Systems, Image Processing, Machine Learning, Computer Organization and Architecture, Introduction to Software Engineering (Agile methodologies, UML, etc), Computer Networks, Operating Systems and Language Theory.
* **Math and Science:** Differential Calculus, Integral Calculus, Engineering Mechanics, Fundamental of Robotics, Fundamentals of Electronics, Digital Electronics
* **Misc:** Effective Communication Skills, Culture and Human values, Engineering Design, Marketing Research and Analysis, Manufacturing Processes, Soft Skills, Indian Philosophy and Literature

I've also done few group based academic projects:
* We Forecasted arrivals and prices and Onions in Indian market using hybrid model of SARIMA and SVM.
* We developed "Fest management system" (backend+frontend) to maintain a wholesome fest (A typical college fest website where someone can register for events and can check their current statuses and more).
* We worked on building lower part (legs) and movement for a four-legged soccer playing robot.(This project failed during presentation, haha)


#### **Non-Traditional**

I'm a strong supporter of education through MOOCs and bootcamps.
* Deep Learning Specialization - DeepLearning.ai, Coursera
* Marketing Reserach and Analysis - IIT Roorkee, Swayam [certificate](https://drive.google.com/file/d/1fs9FRNUo6FU38GZ7omSjEvK-c_WkGQMs/view))
* Practical Machine Learnig with Tensorflow - IIT Madras, Swayam ([certificate](https://drive.google.com/file/d/1xRh1FQtjkVmhthW2E6tGnRgPb3tdj0-R/view))
* CS231n: Convolutional Neural Networks for Visual Recognition - Stanford (Andrej Karpathy)
* CS229: Machine Learning - Stanford (Andrew Ng - Autumn 2018)
* Introduction to Computer Science and Programming Using Python. (Fall 2016) - MITx