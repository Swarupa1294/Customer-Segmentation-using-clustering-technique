# Customer-Segmentation-using-clustering-technique
# 1. Business Problem
# 1.1 Problem Context
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.
* Using machine learning to understand customers behavior
* How to measure distances in machine learning
# Introduction
Every person is different and so is their behavior as customers.
Imagine you are the owner of a shop. It doesn't matter if you own an e-commerce or a supermarket. It doesn't matter if it is a small shop or a huge company such as Amazon or Netflix, it's better to know your customers.
Machine learning comes in handy for this task. Particularly, clustering, the most important unsupervised learning problem, is able to create categories grouping similar individuals.
These categories are called clusters. A cluster is a collection of points in a dataset. These points are more similar between them than they are to points belonging to other clusters. Distance-based clustering groups the points into some number of clusters such that distances within the cluster should be small while distances between clusters should be large.
# Purpose
The goal of this project is to:
* Perform an exploratory analysis on the dataset.
* Check that the assumptions K-means makes are fulfilled.
* Apply K-means clustering algorithm in order to segment customers.
# 1.2 Problems with current approach
Currently, the retailer simply groups their international customers by country. As you`ll see in the project, this is quite inefficient because:
There`s a large number of countries(which kind of defeats the purpose of creating groups)
Some countries have very few customers
# 1.3 Problem Statement
You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

# 1.4 Business Objectives and constraints
# 2. Machine Learning Problem
# 2.1 Data Overview
This file contains the basic information (ID, age, gender, income, spending score) about the customers
* ID- Customer ID
* age - Customer age
* gender - Customer gender
* income- Customer income
* Spending - where customer spends
* Score- What is customer score
# 2.2 Mapping Business problem to ML problem
# 2.2.1 Type of ML problem
It is an unsupervised learning task, where given the features about each transaction, we need to segment the customers based on their buying patterns.
It is importnat to note that the given data is transaction-level while the clusters (or segmenst) we need to create are
# Data Set Information
The csv file corresponding used herein was downloaded from Kaggle repository. The dataset contains data about customers from a Mall. The information gather is: Customer ID, Age, Annual Income (k$), Spending Score (1-100).
# Analysis
This repository contains two files:

* clustering_analysis.ipybn: In this jupyter notebook, exploratory data analysis is performed. Moreover, the algorithm assumptions are checked. K-means is applied to segment customers obtaining a graph and the customer segments. It is also shown how to predict to which segment a new customers belongs to.
customers.csv dataset used to perform the analysis.
* The whole analysis was done using JupyterLab and Python, using libraries such as: pandas, numpy, matplotlib, and scikit-learn.

