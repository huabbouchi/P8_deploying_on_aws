# Deploy a Model in the Cloud

### Table of Contents

- [Introduction](#C1)

    - [Data](#C1.1)

    - [Mission](#C1.2)

    - [Specifications](#C1.3)

<br>

***

## Introduction<a name="C1"></a>
***

I am a Data Scientist at a very young AgriTech startup named ***"Fruits!"***, which aims to provide innovative solutions for fruit harvesting.

![Fruits! Logo](pictures/logo_fruits.png)

The company's goal is to preserve fruit biodiversity by enabling specific treatments for each fruit species through the development of smart picking robots.

In the first phase, the startup aims to gain recognition by offering the general public a mobile application that allows users to take a photo of a fruit and obtain information about it.

For the startup, this application will raise public awareness of fruit biodiversity and establish an initial version of the fruit image classification engine.

Furthermore, the development of the mobile application will allow the construction of an initial version of the required Big Data architecture.

### Data<a name="C1.1"></a>

A dataset already exists, consisting of fruit images and associated labels, which will serve as a starting point for building part of the data processing pipeline.

### Mission<a name="C1.2"></a>

I am tasked with developing a preliminary data processing pipeline in **a Big Data environment**, including **preprocessing** and a **dimensionality reduction** step.

### Specifications<a name="C1.3"></a>

- I must consider in my development that the data volume will increase rapidly after the delivery of this project. Therefore, I will develop **Pyspark scripts** and utilize, for example, **AWS cloud services** to take advantage of a **Big Data architecture (EC2, S3, IAM)**, based on **an EC2 Linux server**.
- Implementing a Big Data architecture under (for example) AWS may require a more powerful server configuration than the one provided for free (EC2 = t2.micro, 1 GB RAM, 8 GB server disk).
