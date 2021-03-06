# ML Engineering on Google Cloud Platform

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)


This repository contains hands-on labs and code samples that demonstrate best practices and patterns for implementing and operationalizing production grade machine learning workflows on Google Cloud Platform. 

## Navigating this repository
This repository is organized into two sections:
- Hands-on Labs
- Code samples

### Hands-on Labs
This section contains a portfolio of hands-on labs designed to support development and delivery of instructor led ML Engineering workshops. Each lab includes the detailed setup instructions and a summary of lab exercises. The labs are grouped into the series that have to be executed in sequence as the subsequent labs depend on the successful outcome of the preceding labs.

It is expected that instructors will pick and choose from the lab portfolio to create a customized workshop.

### Code Samples
This section compiles code samples demonstrating design and code patterns for a variety of ML Engineering topics. Each code sample is standalone and contains a brief description of the illustrated pattern. 

The goal is to create a portoflio of labs that can be utilized in development and delivery of scenario specific demos and workshops. 

- **Series 0x labs**. These labs guide you through the process of provisioning and configuring a reference MLOps environment on GCP. Most other labs rely on the environment configured in these labs. 
    - **lab-00-environment-setup** is a fully automated one-step deployment of the lab environment. 
    - **lab-01-environment-notebook** and **lab-02-environment-kfp** are alternatives to **lab-00-environment-setup** where the provisioning of an AI Platform Notebook instance and Kubeflow Pipelines are two discrete and more granular steps.
    

- **Series 1x labs**. These labs walk you through the process of authoring and operationalizing KFP pipelines that utilize GCP managed services to train and deploy machine learning models:
    
- **Series 2x labs**. These labs teach how to develop and operationalize **Tensorflow Extended (TFX)** pipelines

- **Series 3x labs**. These labs are deep-dives into **TensorFlow Data Validation**, **TensorFlow Transform**, and **TensorFlow Model Analysis** libraries.


## Sample agendas

The labs in this repo can be used to deliver a wide range of workshops. You can find the examples of workshop agendas in **TBD**.

