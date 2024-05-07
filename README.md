# Spam-Detection-In-Iot-devices
https://www.kaggle.com/datasets/taranvee/smart-home-dataset-with-weather-information

## Description
This project addresses the dynamic nature of IoT device security, emphasizing the need for tailored safety measures based on organizational context and user behavior. Leveraging machine learning, it aims to bolster defense mechanisms by intelligently analyzing IoT data streams to mitigate security risks and uphold privacy. By recognizing the diverse applications of IoT devices, from smart security cameras to wearable health monitors, the project seeks to establish robust security protocols that balance the triad of security, privacy, and computational efficiency. Ultimately, it aims to empower organizations in safeguarding their IoT ecosystems against evolving threats while fostering user trust and data integrity.


## Features
- Implementation of machine learning algorithms for spam detection.
- Anomaly detection techniques tailored for IoT devices.
- Real-time monitoring and alerting system.
- Integration with existing IoT frameworks and platforms.

## Proposed Algorithms :
- RANDOM FOREST ALGORITHM
- KNN ALGORITHM
- SUPPORT VECTOR MACHINE
- NAÏVE BAYES CLASSIFIER

# Table of Contents

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Preliminaries](#preliminaries)
4. [Proposed Work](#proposed-work)
5. [Conclusion](#Conclusion)

### Abstract: 
#### Millions of devices with sensors and actuators connected via wired or wireless channels for data transmission make up the Internet of Things (IoT). Spam Detection in IoT utilizing a Machine Learning framework is suggested to accomplish this goal. In this approach, a huge number of input feature sets are used to evaluate five machine learning models using a variety of criteria. Each model uses the enhanced input attributes to calculate a spam score. This rating shows how trustworthy Internet of Things (IoT) devices are based on several factors. The proposed technique is validated using the REFIT Smart Home dataset. In comparison to other current systems, the findings collected demonstrate the effectiveness of the proposed method.

### INTRODUCTION:
#### IoT is taken into account as an interconnected and distributed network of embedded systems communicating through wired or wireless communication technologies. Massive growth and rapid development in the field of the Internet of Things (IoT), makes the presence of IoT devices prevalent in smart homes and smart cities. It is also defined because the network of physical objects or things empowered with limited computation, storage, and communication capabilities is also embedded with electronics (such as sensors and actuators), software, and network connectivity that permits these objects to gather, sometimes process, and exchange data. The things in IoT ask the objects from our lifestyle starting from smart household devices like a smart bulb, smart adapter, smart meter, smart refrigerator, smart oven, AC, temperature sensor, smoke detector, IP camera, to more sophisticated devices like frequency Identification (RFID) devices, heartbeat detectors, accelerometers, sensors in the parking zone, and a variety of other sensors in automobiles, etc.

### PRELIMINARIES: 
#### Before diving into the development of an efficient spam detection technique for IoT devices using machine learning, there are several preliminary aspects to consider. These include:

##### Understanding IoT Devices: Gain a comprehensive understanding of IoT devices, their characteristics, and communication protocols. IoT devices can include various types of interconnected devices such as sensors, actuators, wearables, smart home devices, and industrial equipment. Familiarize yourself with the specific features and limitations of IoT devices in terms of computing power, memory, energy consumption, and network connectivity.
##### Familiarity with Machine Learning: Develop a strong foundation in machine learning concepts and techniques.
##### This includes understanding different types of machine learning algorithms, such as supervised learning (classification, regression), unsupervised learning (clustering, dimensionality reduction), and reinforcement learning. Learn about common evaluation metrics, feature extraction methods, model training, and model evaluation techniques.

##### Data Collection and Preprocessing: This is the first real step towards the real development of a machine learning model, collecting data. This is a critical step that will cascade in how good the model will be, the more and better data that we get, the better our model will perform.There are several techniques to collect the data, like web scraping, manual interventionsand etc.REFIT Smart Home dataset Link:https://www.refitsmarthomes.org/datasets/

##### Dataset:In this data set we are taken 32 columns and 503910 rows in the dataset,

###### Data Preparation:we will transform the data. By getting rid of missingdata and removing some columns. First we will create a list of column names that we want to keep or retain.Next we drop or remove all columns except for the columns that we want to retain.Finally we drop or remove the rows that havemissing values from the data set.

##### Model Selection: While creating a machine learning model, we need two datasets, one for training and another for testing. But now we have only one. So let's split this in two with a ratio of 80:20. We will also divide the dataframe into feature column and label column.Here we imported the train_test_split function of sklearn. Then use it to split the dataset. Also, test_size = 0.2, it makes the split with 80% as train dataset and 20% as test dataset.
##### Analyze and Prediction: In the actual dataset, we chose only 22 features.
##### Accuracy on test set: We got an accuracy of 99.1% on the test set.
##### Saving the Trained Model: Once you’re confident enough to take your trained and tested model into the production-ready environment, the first step is to save it into a .h5 or . pkl file using a library like pickle .Make sure you have pickle installed in your environment.Next, let’s import the module and dump the model into .pkl file.

##### Deployment and Continuous Improvement: Choose a suitable deployment approach based on the IoT device's capabilities and constraints. Itcould involve deploying the model directly on the device, on a gateway device, or in a cloud-based service.Adapt service.Adapt the model to the target deployment environment, considering resource limitations, computational capabilities, and network connectivity.Implement the necessary infrastructure and integration to facilitate the deployment, including appropriate APIs, data preprocessing pipelines, and communication protocols.Byfollowing these steps, you can deploy an efficient spam detection technique for IoT devices using machine learning and ensure continuous improvement over time. Regular updates, feedback collection, retraining, and performance monitoring are key elements in maintaining a robust and effective spam detection system in the dynamic IoT environment.

### Proposed Work:
###### The proposed approach detects the spam parameters causing the IoT devices to be affected. To get the best results, the IoT dataset is used for the validation of proposed approach as described in the next Section. The proposed framework,  detects the spam parameters using machine learning models. The IoT dataset used for experiments, is pre-processed by using feature engineering procedure. By experimenting the framework with machine learning models, each appliance is awarded with a spam score. This refines the conditions to be taken for successful working on devices in a smart home. 

### Conclusion : 
#### To effectively detect spam in IoT devices, it is important to carefully consider the unique characteristics of the devices and the data being analyzed, and to use a combination of techniques to achieve the best possible results. Additionally, it is important to monitor and adapt to changes in the data and to continuously update and improve the spam detection system to keep up with evolving spam and other malicious activity. Overall, spam detection in IoT devices is a crucial task for ensuring the security and reliability of IoT systems, and ongoing research and development in this area will be critical for the continued growth and success of the IoT industry. 
